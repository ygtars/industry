
Debian
====================
This directory contains files used to package idyd/idy-qt
for Debian-based Linux systems. If you compile idyd/idy-qt yourself, there are some useful files here.

## idy: URI support ##


idy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install idy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your idyqt binary to `/usr/bin`
and the `../../share/pixmaps/idy128.png` to `/usr/share/pixmaps`

idy-qt.protocol (KDE)

