
Debian
====================
This directory contains files used to package privatd/privat-qt
for Debian-based Linux systems. If you compile privatd/privat-qt yourself, there are some useful files here.

## privat: URI support ##


privat-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install privat-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your privat-qt binary to `/usr/bin`
and the `../../share/pixmaps/privat128.png` to `/usr/share/pixmaps`

privat-qt.protocol (KDE)

