
Debian
====================
This directory contains files used to package voltnoted/voltnote-qt
for Debian-based Linux systems. If you compile voltnoted/voltnote-qt yourself, there are some useful files here.

## voltnote: URI support ##


voltnote-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install voltnote-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your voltnote-qt binary to `/usr/bin`
and the `../../share/pixmaps/voltnote128.png` to `/usr/share/pixmaps`

voltnote-qt.protocol (KDE)

