dmenu - dynamic menu
====================
build by John DeSalvo


Installation
------------
This build installs to /opt by default so either:
* make sure /opt/bin is in your $PATH, or
* change config.mk as desired and install it wherever

Afterwards enter the following command to build and install dmenu
(if necessary as root):

        make install

        make clean

In order to build dmenu you need the Xlib header files.

Basic
-----
* to use as an application launcher:

        dmenu_run
* to display standard output:

        ... | dmenu 

See the man page for details.
