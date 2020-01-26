
Debian
====================
This directory contains files used to package micropaymentcoind/micropaymentcoin-qt
for Debian-based Linux systems. If you compile micropaymentcoind/micropaymentcoin-qt yourself, there are some useful files here.

## micropaymentcoin: URI support ##


micropaymentcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install micropaymentcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your micropaymentcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/micropaymentcoin128.png` to `/usr/share/pixmaps`

micropaymentcoin-qt.protocol (KDE)

