
Debian
====================
This directory contains files used to package francd/franc-qt
for Debian-based Linux systems. If you compile francd/franc-qt yourself, there are some useful files here.

## franc: URI support ##


franc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install franc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your francqt binary to `/usr/bin`
and the `../../share/pixmaps/franc128.png` to `/usr/share/pixmaps`

franc-qt.protocol (KDE)

