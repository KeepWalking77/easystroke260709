Easystroke 20260709

Mouse Gesture Application for Linux X11

A modern rebuild of Easystroke with updated build system and Debian package support for modern Ubuntu systems.

Easystroke allows you to control your computer by drawing gestures with your mouse. Create custom mouse movements and assign actions such as keyboard shortcuts, commands, scrolling, and window controls.

Features
Mouse gesture recognition
Custom gesture actions
Keyboard shortcut simulation
Run shell commands
Mouse button emulation
Scroll simulation
Modifier key support
System tray integration
Lightweight and fast
Native X11 support
Supported Systems

Tested on:

Ubuntu 26.04
Ubuntu MATE 26.04
X11 Session

Wayland support is not guaranteed. Easystroke requires X11 features.

Installation
Install from Debian package

Download the latest .deb package from Releases.

Example:

sudo apt install ./easystroke_pkg.deb

Dependencies will be installed automatically.

Build From Source

Install required packages:

sudo apt update

sudo apt install \
build-essential \
git \
libboost-all-dev \
libgtk2.0-dev \
libxtst-dev \
libx11-dev \
pkg-config

Clone repository:

git clone https://github.com/KeepWalking77/easystroke260709.git

cd easystroke260709

Build:

make

Install:

sudo make install

Run:

easystroke
Create Debian Package

Install packaging tools:

sudo apt install devscripts debhelper

Build:

dpkg-buildpackage -us -uc

Generated package:

../easystroke_*.deb
Usage

Start Easystroke:

easystroke
