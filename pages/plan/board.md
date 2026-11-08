# The board

The board is the plan, drawn the way a consulting plan slide is: a stack of
rows under a time scale, lined off into workstreams.

![The plan board](../img/plan.png)

## Rows

A row is a line on the board. It holds as many activities and milestones as
fit side by side, so a row reads as a flow: activity one, two and three, then
a milestone. Rows have no names of their own; what's on them carries the
names.

- Something you add next to an item lands on that item's row.
- When two items on a row overlap in time, one goes down a lane, so nothing is
  ever hidden. It stays in that lane until you drag it back up.
- A row that a drag or a delete empties closes up by itself, unless it's its
  workstream's only row.
- Below the last row there's always room to start a new one.

Right-click a row for **Add an empty row below** or, when it's empty,
**Remove this row**. **Arrange rows by work package** (right-click free space)
rebuilds the rows from the work packages within each workstream; undo puts your own
arrangement back.

## The time scale

Choose **Days**, **Weeks** or **Months** in the toolbar for how much time a
column shows. Months are labelled in bold, then weeks by their number with
the Monday's date.

- The board shows working days only. Saturday and Sunday take no room, so
  every week is five columns wide.
- Today is a dashed line down the board.
- [Holidays](holidays.md) are grey bands, named at the top.

## Zoom

The zoom control beside **Days**, **Weeks** and **Months** makes everything
on the plan bigger or smaller, from 50% to 200%. Click the percentage to go
back to 100%. You can also hold <kbd>Ctrl</kbd> and scroll, or pinch on a
trackpad.

Zoom changes how big the plan is; Days, Weeks and Months change how much time
a column is. Both are remembered in your browser.

## Looking around

Scroll, drag the time scale, or hold the right mouse button and pull. A
right-click without moving still opens the menu.

## Who can change it

Owners and editors can change the plan. Viewers see exactly the same board,
without the handles: they can't drag, stretch or rename anything.
