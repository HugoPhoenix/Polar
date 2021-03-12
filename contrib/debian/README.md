
Debian
====================
This directory contains files used to package polard/polar-qt
for Debian-based Linux systems. If you compile polard/polar-qt yourself, there are some useful files here.

## polar: URI support ##


polar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install polar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your polar-qt binary to `/usr/bin`
and the `../../share/pixmaps/polar128.png` to `/usr/share/pixmaps`

polar-qt.protocol (KDE)

