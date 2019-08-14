![](https://github.com/nmilford/stormLauncher/raw/master/stormLauncher.png)

# Instructions

Tested on Ubuntu 16.04

### Setup

This will create a python virtual environment and install dependancies to it, so the launch script works

`bash setup.sh`

### Run it

`sudo bash launch.sh`



# Storm Launcher

Controls the Dream Cheeky [O.I.C Storm](http://www.dreamcheeky.com/storm-oic-missile-launcher) & [Thunder](http://www.dreamcheeky.com/thunder-missile-launcher) USB Missile Launchers.  

There are a few projects for using older launchers in Linux, but I couldn't find any for this launcher, so... enjoy.

This script requires PyUSB 1.0+, apt in Debian/Ubuntu installs 0.4.

Also, on Debian\Ubuntu systems you need the __python-imaging-tk__
    
It also requires that you run it as root unless you want to spend an afternoon playing with udev rules :/

## Getting Started:

    git clone git@github.com:nmilford/stormLauncher.git
    cd stormLauncher
    chmod +x stormLauncher.py
    sudo ./stormLauncher.py

## Usage:

* Use arrow keys aim.
* Press return to fire.
