# Settings

Choose **Settings** in the header. It holds your own settings and, for
account managers, the account's.

![Settings](../img/settings.png)

## Your profile

Your name, as everyone sees it, and your email. **Download my data** gives you
everything Steerboard holds about you, as a file.

**Email me about my work** is ticked to start with: projects that send email
about their work (see [Project settings](../project-settings.md#emails-about-work))
send you yours. Untick it to get none.

## Password

Enter your current password and a new one of at least 10 characters. You stay
signed in where you are; other devices are signed out.

## Account (account managers)

| Section | What it does |
|---|---|
| **Account name** | Everyone in the account sees it, and so do the people you invite. |
| **Subscription** | The account's tier and what it holds: how many seats it has (planners and account managers each take one, and so does an invitation to become one; viewers and contributors are free), how many projects the account keeps (archived ones count), how many people it can hold, and how many items a project's plan can hold. See [The subscription](#the-subscription). |
| **Who can add people** | Who may bring in people who sign in: account managers only, planners too as viewers and contributors, or planners at any level. See [People and groups](people.md#who-can-invite). |
| **Links without signing in** | Whether a project's owner can turn on a view-only link to its status report: see [Sharing a project](sharing.md#a-link-that-opens-without-signing-in). Untick **Projects can have a view-only link** and no project can turn one on, and links that were on stop opening until it's ticked again. |
| **Account owner** | Whose the account is, and **Hand over…** for handing it to another account manager. See [People and groups](people.md#the-account-owner). |
| Single sign-on | Your company's email domains, a setup link for your IT to connect your identity provider, and whether everyone must use it. Account managers can always still use their password. |
| Audit log | Who did what in the account, and when: sign-ins, invitations, roles, sharing, projects and billing. |
| Your account's data | Everything in the account, as one file. |

The account's people and groups are on the [People](people.md) page.

## The subscription

An account's subscription is on a tier. The tier sets how many seats the
account has, how many people it can hold in all, how many projects it keeps,
and how many items (activities, milestones and work packages) one project's
plan can hold. It also says which of these the account has: your own logo and
a client's template on the slides, emails about work and reports, project
owners inviting people, single sign-on, the audit log, and the account's data
as a file.

Steerboard is in early access for now. Every account has all of it and nothing
is charged, within 100 seats, 1,000 people, 20 projects and 1,000 items on a
project. **Subscription** says so, and shows where the account stands under
**Seats taken**, **Projects** and **People**.

When something would go past a limit, Steerboard says so and doesn't do it:
the invitation isn't sent, the project isn't created, or the change to the
plan isn't saved. A project already over its limit can still be changed and
made smaller, but not bigger.

### Choosing a tier

When tiers apply, a new account starts on the one that costs nothing, and
**Subscription** lists what it holds. **See the tiers** puts the tiers side by
side, with what each holds and what a seat costs, billed **Yearly** or
**Monthly**. Choose one, say how many seats you need, and pay on Stripe's
checkout page. You come back to Settings, and the account is on its new tier
within a minute.

Only planners and account managers need a seat. Viewers, contributors and
people who don't sign in are free on every tier.

After that:

- **Change tier** moves the account to another tier, or to the other way of
  paying. Stripe works out the difference for the time left.
- **Paid seats** and **Change seats** add seats or give some back, never
  fewer than are taken.
- **Invoices and payment** opens Stripe's page for your invoices, your card,
  and your company's address and tax number.
- **Cancel the subscription** is among the tiers, under the one that costs
  nothing. The subscription runs to the end of what's paid for. Until then
  **Keep the subscription** takes the cancellation back.

When a subscription ends, the account is back on the tier that costs nothing,
and nothing is deleted. What that tier doesn't include is locked. What's over
its limits stays and can't grow: the planners keep their seats and the
projects stay, and no more can be added until there's room.

Something the account's tier doesn't include shows where it would be, with a
lock, so you know it's there.
