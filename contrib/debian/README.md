
Debian
====================
This directory contains files used to package estatequeryd/estatequery-qt
for Debian-based Linux systems. If you compile estatequeryd/estatequery-qt yourself, there are some useful files here.

## estatequery: URI support ##


estatequery-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install estatequery-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your estatequery-qt binary to `/usr/bin`
and the `../../share/pixmaps/estatequery128.png` to `/usr/share/pixmaps`

estatequery-qt.protocol (KDE)

