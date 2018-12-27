
Debian
====================
This directory contains files used to package iexd/iex-qt
for Debian-based Linux systems. If you compile iexd/iex-qt yourself, there are some useful files here.

## iex: URI support ##


iex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install iex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your iexqt binary to `/usr/bin`
and the `../../share/pixmaps/iex128.png` to `/usr/share/pixmaps`

iex-qt.protocol (KDE)

