# Graphical yad front-end to xwd, 'yet another xwd shot (yaxshot)'
A tiny bash script to grab a shot of the desktop or a particular window inside X11.
This script depends on netpbm (xwdtopnm, pnmtojpeg, pnmtopng and pnmtotiff), GNU date, xwd and yad (yet another dialog).
On a usual GNU/Linux distribution, these programs are easily obtained through the package manager.

To use this script, make sure you've got the above programs installed, then issue:
$ cp yaxshot /usr/local/bin #copy yaxshot to /usr/local/bin or /usr/bin, whichever location you prefer

# Features
Output screenshots as PNG, TIFF or JPEG<br>
Specify a delay (in seconds) before capturing a screenshot
Automatic filename generation based on the current time and date
Capture the entire desktop or individual windows

It's really just a small little tiny, but useful script with a gui.
It's much faster to just use the command line, 
but... on those late nights of procastination, why bother to event think? Just click that mouse button instead
