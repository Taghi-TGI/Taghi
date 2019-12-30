
Debian
====================
This directory contains files used to package taghid/taghi-qt
for Debian-based Linux systems. If you compile taghid/taghi-qt yourself, there are some useful files here.

## taghi: URI support ##


taghi-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install taghi-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your taghiqt binary to `/usr/bin`
and the `../../share/pixmaps/taghi128.png` to `/usr/share/pixmaps`

taghi-qt.protocol (KDE)

