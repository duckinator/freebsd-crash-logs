# Details

Roughly every 14-20 days I walk away from my desktop for a bit, and
come back to the same problem:

- the system is at a console (not Xorg, as it was when I left)
- the console has no text; only a gray square in the top-left and the mouse cursor added by moused on a VT.

System info:

- Ryzen 7 2700
- 48GB RAM
- 1TB SSD

Here's all the information I have:

- It happens every 14-20 days.
- It's happened at least 4 times.
- It has _never_ happened while anyone is looking at the display.
- I know for a fact nobody is locally tampering with my system (and there's no animals/pets to do so).
- It runs out of swap, despite it usually having 40GB+ RAM free when I walk away.
- After running out of swap, it kills 75-85 processes, which is notable for being *nearly every freaking process on the system*.
- The logs show most of them being killed *the same second*, but I suspect there is some logging delay introduced by whatever is happening.
