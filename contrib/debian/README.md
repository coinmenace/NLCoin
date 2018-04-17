
Debian
====================
This directory contains files used to package Protond/Proton-qt
for Debian-based Linux systems. If you compile Protond/Proton-qt yourself, there are some useful files here.

## Proton: URI support ##


Proton-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Proton-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Proton-qt binary to `/usr/bin`
and the `../../share/pixmaps/Proton128.png` to `/usr/share/pixmaps`

Proton-qt.protocol (KDE)

