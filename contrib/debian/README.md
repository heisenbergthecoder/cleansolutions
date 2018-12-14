
Debian
====================
This directory contains files used to package cleansolutionsd/cleansolutions-qt
for Debian-based Linux systems. If you compile cleansolutionsd/cleansolutions-qt yourself, there are some useful files here.

## cleansolutions: URI support ##


cleansolutions-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cleansolutions-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cleansolutionsqt binary to `/usr/bin`
and the `../../share/pixmaps/cleansolutions128.png` to `/usr/share/pixmaps`

cleansolutions-qt.protocol (KDE)

