
Debian
====================
This directory contains files used to package gofundd/gofund-qt
for Debian-based Linux systems. If you compile gofundd/gofund-qt yourself, there are some useful files here.

## gofund: URI support ##


gofund-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gofund-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gofundqt binary to `/usr/bin`
and the `../../share/pixmaps/gofund128.png` to `/usr/share/pixmaps`

gofund-qt.protocol (KDE)

