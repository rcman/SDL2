# Allegro5
Building SDL2 on Linux using SCONS


you need to install scons and python

sudo apt install scons
sudo apt install python3

For SDL2 you need to install all SDL dev library on your box

The SConstrct file

This file looks for these directories

include
src
release


Place all your sound and gfx inside the release dir and the executable will be there

Place source and include in their respective directories

Once you have all that done all you need to do in run scons at the command line

NOTE: You may need to edit the SConstuct to add additional libraries

Right now the line in the file shows: SDL2_image SDL2_mixer SDL2_ttf

Add whatever you need

The Shell I use to install everything for SDL2

#!/bin/sh



sudo apt install binutils -y
sudo apt install build-essential -y
sudo apt install scons -y
sudo agt install gedit gedit-plugins
sudo apt install wget
sudo apt install ibsdl2-dev -y
sudo apt install libsdl2-gfx-dev -y
sudo apt install libsdl2-image-dev -y
sudo apt install libsdl2-mixer-dev -y
sudo apt install libsdl2-net-dev -y
sudo apt install libsdl2-ttf-dev -y
sudo apt install imagemagick -y
sudo apt install rar -y
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt update
sudo apt install code
