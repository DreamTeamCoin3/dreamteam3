
Debian
====================
This directory contains files used to package dreamteam3d/dreamteam3-qt
for Debian-based Linux systems. If you compile dreamteam3d/dreamteam3-qt yourself, there are some useful files here.

## dreamteam3: URI support ##


dreamteam3-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dreamteam3-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dreamteam3qt binary to `/usr/bin`
and the `../../share/pixmaps/dreamteam3128.png` to `/usr/share/pixmaps`

dreamteam3-qt.protocol (KDE)

