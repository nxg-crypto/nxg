
Debian
====================
This directory contains files used to package nodexchanged/nodexchange-qt
for Debian-based Linux systems. If you compile nodexchanged/nodexchange-qt yourself, there are some useful files here.

## nodexchange: URI support ##


nodexchange-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodexchange-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodexchangeqt binary to `/usr/bin`
and the `../../share/pixmaps/nodexchange128.png` to `/usr/share/pixmaps`

nodexchange-qt.protocol (KDE)

