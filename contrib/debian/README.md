
Debian
====================
This directory contains files used to package coinmegatrendd/coinmegatrend-qt
for Debian-based Linux systems. If you compile coinmegatrendd/coinmegatrend-qt yourself, there are some useful files here.

## coinmegatrend: URI support ##


coinmegatrend-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install coinmegatrend-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your coinmegatrendqt binary to `/usr/bin`
and the `../../share/pixmaps/coinmegatrend128.png` to `/usr/share/pixmaps`

coinmegatrend-qt.protocol (KDE)

