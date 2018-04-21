
Debian
====================
This directory contains files used to package hitexd/hitex-qt
for Debian-based Linux systems. If you compile hitexd/hitex-qt yourself, there are some useful files here.

## hitex: URI support ##


hitex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hitex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hitexqt binary to `/usr/bin`
and the `../../share/pixmaps/hitex128.png` to `/usr/share/pixmaps`

hitex-qt.protocol (KDE)

