# Activities and milestones

An *activity* is work that takes time. It's drawn as a boat:
square at the start, pointed at the end. A *milestone* is a moment, such as a
sign-off or a steering committee. It's drawn as a diamond.

## Add one

| To add | Do this |
|---|---|
| An activity | Right-click free space on a row and choose **New activity here**. Or hold <kbd>Alt</kbd> and draw across free space on a row. Or drag **Activity** from the toolbar onto the board, or click it to add one on a new row at the bottom. |
| A milestone | Right-click a spot on a row and choose **New milestone here**, or drag **Milestone** from the toolbar onto the board. |
| A new row | Right-click in the space below the rows (or hold <kbd>Alt</kbd> and draw there), or drop something on the line between two rows (a blue line shows where). |

Drawing without <kbd>Alt</kbd> doesn't add anything: it pulls a box that
[selects](#select-several) what it touches.

A new activity lasts one working week unless you draw it to size. Type its
name straight away; <kbd>Enter</kbd> keeps it.

Everything you add starts as a draft, pencilled in with a dashed outline,
until you [agree its dates](agreed-dates.md), and it can't start until then.

![The menu on an activity](../img/plan-menu.png)

## Move and resize

| To | Do this |
|---|---|
| Move it in time | Drag it left or right. |
| Move it to another row | Drag it up or down. The row lights up and an outline shows where it lands. Drop it on the line between two rows for a new row there. |
| Change an activity's dates | Drag either end. Milestones have a single date. |
| Rename it | Double-click it, or select it and press <kbd>Enter</kbd>. The name becomes editable where it is. |
| Delete it | Right-click it and choose **Delete activity** (or **Delete milestone**), drop it on the bin that appears while you drag, or press <kbd>Delete</kbd>. |

What you drag is what you get: the edge you hold follows the pointer column by
column, a tip shows the dates, and when you let go it stays where it was
shown. Nothing else on the board moves by itself, except work that
[waits for it](links.md) when it would otherwise start too early.

Starts, ends and milestones always fall on working days.

## Select several

Press on free space and pull a box across the board: everything the box
touches is selected, activities, milestones and work packages alike. Nothing
is added. Hold <kbd>Shift</kbd> or <kbd>Ctrl</kbd> while you pull to add to
what's already selected, or <kbd>Ctrl</kbd>-click or <kbd>Shift</kbd>-click
items one by one.

With several selected you can:

- Drag one of them sideways to move them all in time. Each stays on its own
  row, and the tip says how many are moving and how far. <kbd>←</kbd> and
  <kbd>→</kbd> move them all a working day.
- Agree their dates, mark them done, give them to someone, move them to a
  workstream or delete them, from
  the details panel.
- Right-click one of them for the same, or for **Put in a new work package**
  to put a bracket over them.
- Press <kbd>Delete</kbd>, or drop them on the bin, to delete them all. That's
  one step to undo.

A work package that's selected takes what's inside it along. A click on free
space clears the selection.

To give one activity sub-activities, right-click it and choose
**Add a sub-activity**: see [work packages](workstreams.md#work-packages).

Click blank canvas, the time scale or the column of workstreams, or press
<kbd>Escape</kbd>, to deselect.

## Names

Every name shows somewhere it can be read, and never over anything else:
inside the item when it fits, otherwise beside it, otherwise shortened with
"…". Point at an item to see its whole name.

A name is kept on one line, up to 200 letters. Cleared, it stays the name it
was.

To see who owns what, choose **Show** in the toolbar and tick **Owners**. Each
item's owner then follows its name as initials, as in "Elasticity model (PN)";
a work package shows its lead. The choice is kept in your browser, and the
report's [plan slide](../report/present.md#the-plan-slide) follows it.

## Undo

<kbd>Ctrl</kbd>+<kbd>Z</kbd> undoes and <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Z</kbd>
redoes, or use the arrows in the toolbar. Undo takes back only your own
changes.
