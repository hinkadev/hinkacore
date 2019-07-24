
Debian
====================
This directory contains files used to package hinkad/hinka-qt
for Debian-based Linux systems. If you compile hinkad/hinka-qt yourself, there are some useful files here.

## hinka: URI support ##


hinka-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hinka-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hinkaqt binary to `/usr/bin`
and the `../../share/pixmaps/hinka128.png` to `/usr/share/pixmaps`

hinka-qt.protocol (KDE)

