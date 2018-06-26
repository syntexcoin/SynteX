
Debian
====================
This directory contains files used to package syntexd/syntex-qt
for Debian-based Linux systems. If you compile syntexd/syntex-qt yourself, there are some useful files here.

## syntex: URI support ##


syntex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install syntex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your syntexqt binary to `/usr/bin`
and the `../../share/pixmaps/syntex128.png` to `/usr/share/pixmaps`

syntex-qt.protocol (KDE)

