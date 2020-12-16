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
