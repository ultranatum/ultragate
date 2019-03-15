
Debian
====================
This directory contains files used to package ultragated/ultragate-qt
for Debian-based Linux systems. If you compile ultragated/ultragate-qt yourself, there are some useful files here.

## ultragate: URI support ##


ultragate-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ultragate-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ultragateqt binary to `/usr/bin`
and the `../../share/pixmaps/ultragate128.png` to `/usr/share/pixmaps`

ultragate-qt.protocol (KDE)

