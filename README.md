LxQt-SlackBuilds
=================

SlackBuilds of mine for Qt5 version of LxQt

These are for Slackware Current as of 2/07/2015

Won't work on Stock Slackware 14.1

##########################
## Slackware 14.1 Notes ##
##########################

I got Lxqt working on Slackware-14.1

You need to upgrade the following packages from current prior to installing Qt5.

1. libxcb
2. xcb-proto
3. xcb-util-curser
4. xcb-util-renderutil
5. xcb-util-wm

If you have Multilib setup like I do upgrade the libxcb package with the one
from the Slackware current Mulitlib.
