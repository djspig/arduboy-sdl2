Arduboy for Mac and PC using SDL 2.0
============

This is a project for building and running Arduboy projects with SDL 2.0 on your Mac and PC.  Intended to make it easier to develop for the Arduboy.

Inspired by https://github.com/stg/arduboy-for-pc

For Mac
============
1. Install SDL 2.0 framework from https://www.libsdl.org/download-2.0.php
2. Build the desired sketch by running:
..* `make SKETCH=HelloWorld` where `HelloWorld` is a directory under ./sketches
3. Run the sketch
..* `./bin/HelloWorld`
4. Clean up
..* `make clean SKETCH=HelloWorld`

For PC
============
1. Install MinGW.
2. Install SDL 2.0 development headers in MinGW.
3. ...