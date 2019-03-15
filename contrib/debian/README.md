
Debian
====================
This directory contains files used to package otscoind/otscoin-qt
for Debian-based Linux systems. If you compile otscoind/otscoin-qt yourself, there are some useful files here.

## otscoin: URI support ##


otscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install otscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your otscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/otscoin128.png` to `/usr/share/pixmaps`

otscoin-qt.protocol (KDE)

