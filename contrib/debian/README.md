
Debian
====================
This directory contains files used to package Arnestad/Arnesta-qt
for Debian-based Linux systems. If you compile Arnestad/Arnesta-qt yourself, there are some useful files here.

## Arnesta: URI support ##


Arnesta-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Arnesta-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Arnestaqt binary to `/usr/bin`
and the `../../share/pixmaps/Arnesta128.png` to `/usr/share/pixmaps`

Arnesta-qt.protocol (KDE)

