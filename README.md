# Steerboard docs

The user documentation for [Steerboard](https://steer-board.com), published at
[docs.steer-board.com](https://docs.steer-board.com). It's a
[MkDocs Material](https://squidfunk.github.io/mkdocs-material/) site: Markdown
pages in `pages/`, the navigation in `mkdocs.yml`, the look in
`pages/assets/stylesheets/steerboard.css`.

The docs are written in the planner repository, beside the app, so a change to
the app and the change to its docs go in one commit. This folder is then
published to its own repository, where GitHub Pages builds it.

## Writing

- **Bold means "what you see on screen"**: a button, menu item, field, tab or
  column, written exactly as the app writes it, including its "…". Nothing
  else is bold, except a term being defined, which ends in a full stop
  (`**Draft.** Work whose…`). The tests check every bold label against the
  app's source, so a renamed button can't leave the docs behind.
- Plain words, sentence case, short sentences: the app's own voice. Activities,
  milestones, workstreams, groups, agreed dates, drafts.
- Pictures are real screenshots of the app, in `pages/img/`. Don't edit them by
  hand: `npm run screens` (in the planner) takes them all again from a fresh,
  throwaway copy of the app with the demo engagement. Add a shot to `SHOTS` in
  `scripts/screens.ts` when a page needs a new one.
- Each page is listed in `coverage.json` with the source files it describes.

## Keeping it up to date

When a change alters what people see or do:

1. Update the page that describes it, in the same commit. `coverage.json` says
   which page covers which files.
2. If a screenshot shows the changed screen, run `npm run screens`.
3. Run `npm run docs:check`. It fails on a label the app no longer shows, a
   dead link or picture, or a page missing from the nav (the tests run the same
   check, so a release can't ship them). It also warns about pages whose
   source files changed in later commits than the page.
4. If a warned page is still right as it is, say so:
   `npm run docs:check -- --reviewed plan/items.md`, and commit
   `coverage.json`.

`npm run release` prints the same warnings before it starts.

## Previewing

```
pip install -r docs/requirements.txt
npm run docs:serve
```

Then open http://127.0.0.1:8000. `mkdocs build --strict -f docs/mkdocs.yml`
is what the deploy runs; it fails on any warning.

## Publishing

`npm run docs:publish` checks the docs, splits `docs/` out of the planner's
history (`git subtree split`) and pushes it to the `main` branch of the `docs`
remote. The workflow in `.github/workflows/deploy.yml` builds and deploys it.

Once, before the first publish:

1. Create an empty repository on GitHub, for example `steerboard-docs`.
2. `git remote add docs https://github.com/<you>/steerboard-docs.git`
3. In the repository's Settings → Pages, set Source to **GitHub Actions** and
   the custom domain to `docs.steer-board.com`.
4. At the domain's DNS, add a CNAME record: `docs` → `<you>.github.io`.

`requirements.txt` pins MkDocs below 2.0 on purpose: 2.0 removes the plugin
system and theme overrides this site uses.
