
Debian
====================
This directory contains files used to package runecashd/runecash-qt
for Debian-based Linux systems. If you compile runecashd/runecash-qt yourself, there are some useful files here.

## runecash: URI support ##


runecash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install runecash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your runecashqt binary to `/usr/bin`
and the `../../share/pixmaps/runecash128.png` to `/usr/share/pixmaps`

runecash-qt.protocol (KDE)

