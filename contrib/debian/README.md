
Debian
====================
This directory contains files used to package rwtalerd/rwtaler-qt
for Debian-based Linux systems. If you compile rwtalerd/rwtaler-qt yourself, there are some useful files here.

## rwtaler: URI support ##


rwtaler-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rwtaler-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rwtaler-qt binary to `/usr/bin`
and the `../../share/pixmaps/rwtaler128.png` to `/usr/share/pixmaps`

rwtaler-qt.protocol (KDE)

