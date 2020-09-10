
Debian
====================
This directory contains files used to package savingd/saving-qt
for Debian-based Linux systems. If you compile savingd/saving-qt yourself, there are some useful files here.

## saving: URI support ##


saving-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install saving-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your saving-qt binary to `/usr/bin`
and the `../../share/pixmaps/saving128.png` to `/usr/share/pixmaps`

saving-qt.protocol (KDE)

