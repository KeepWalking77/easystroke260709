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

### Install from Debian Package

Before installing Easystroke, install the required dependencies:

```bash
sudo apt update

sudo apt install \
    libboost-serialization1.88.0 \
    libboost-program-options1.88.0 \
    libboost-filesystem1.88.0 \
    libboost-system1.88.0 \
    libgtk2.0-0 \
    libxtst6
```

Download the latest **.deb** package from the **Releases** page.

Install it with:

```bash
sudo apt install ./easystroke_20260709_*.deb
```


### Build from Source

Install the required build dependencies:

```bash
sudo apt update

sudo apt install \
    build-essential \
    git \
    libboost-all-dev \
    libgtk2.0-dev \
    libxtst-dev \
    libx11-dev \
    pkg-config
```

Clone the repository:

```bash
git clone https://github.com/KeepWalking77/easystroke260709.git

cd easystroke260709
```

Build:

```bash
make
```

Install:

```bash
sudo make install
```

Run:

```bash
easystroke
```
