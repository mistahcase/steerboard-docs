# Links between work

A link means "B can't start until A is finished". It's drawn as a fine dotted
line from A's end to B's start, with an arrow into B.

## Make a link

- Point at A and drag the small blue dot at its end onto B. Or click the dot,
  then click B.
- Or right-click B, choose **Starts after…**, then click A.
- Or right-click A, choose **Followed by…**, then click B.
- Or use **Add** under "Starts after" or "Followed by" in the
  [details panel](details.md).

While you drag, the item you'd link to is ringed in blue, or in red if the
link isn't allowed (it would go round in a circle, for example).

Dropping one item on another only moves it. It never links them.

## What a link does

B starts on the next working day after A ends, or later. The gap between them
can be anything.

- Moving A, or making it longer, leaves B where it is until A would end on or
  after the day B starts. Then B is pushed to start the day after A ends, and
  anything waiting on B is pushed in turn if it needs to be.
- B is never pulled earlier.
- B can't be put before the day after A ends. Moved or typed earlier, it stops
  at the first day it can start; a start pulled earlier stops there too, and
  its end stays where it was.
- A link to or from a work package applies to everything in it. In a package
  that waits, a piece moved too early is held the same way, and the rest of
  the package stays where it is.

## What a milestone depends on

Open a milestone's [details](details.md) and choose **What this depends on**.
The linked work leading to it stays lit on the plan and everything else fades.
The panel lists that work, nearest first, with the room each step has: the
working days between its end and the start of what waits for it.

Steps with no room to spare are marked, and a sentence names them: a day late
there is a day late on the milestone. Finished work says done, since it can't
run late any more. Choose a step to open it.

This changes only what's shown: nothing on the plan moves. Choose
**Stop showing what this depends on**, or close the details, to end it.

## Remove a link

Right-click its line and choose **Delete dependency**, or use the × beside it
in the details panel.
