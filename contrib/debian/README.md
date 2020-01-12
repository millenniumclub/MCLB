
Debian
====================
This directory contains files used to package millenniumclubcoind/millenniumclubcoin-qt
for Debian-based Linux systems. If you compile millenniumclubcoind/millenniumclubcoin-qt yourself, there are some useful files here.

## millenniumclubcoin: URI support ##


millenniumclubcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install millenniumclubcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your millenniumclubcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/millenniumclubcoin128.png` to `/usr/share/pixmaps`

millenniumclubcoin-qt.protocol (KDE)

