
Debian
====================
This directory contains files used to package cjzcoind/cjzcoin-qt
for Debian-based Linux systems. If you compile cjzcoind/cjzcoin-qt yourself, there are some useful files here.

## cjzcoin: URI support ##


cjzcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cjzcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cjzcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/cjzcoin128.png` to `/usr/share/pixmaps`

cjzcoin-qt.protocol (KDE)

