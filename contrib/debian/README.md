
Debian
====================
This directory contains files used to package IDYd/IDY-qt
for Debian-based Linux systems. If you compile IDYd/IDY-qt yourself, there are some useful files here.

## IDY: URI support ##


IDY-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install IDY-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your IDYqt binary to `/usr/bin`
and the `../../share/pixmaps/IDY128.png` to `/usr/share/pixmaps`

IDY-qt.protocol (KDE)

