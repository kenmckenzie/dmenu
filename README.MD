dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X. custom version with additional patches.

Patches Added
-------------
lineheight
mouse support
prefixcompletion
xyw (for my rice)

Please read the relevent documentation on suckless'es website for more info on the patches and what they do

Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.

Credits
-------
All the original suckless devs

Huge thank you to https://github.com/bakkeby for flexipatch which helped me include all the patches without days of troubleshooting 