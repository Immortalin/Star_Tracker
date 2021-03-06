# Star Tracker <br />

## Overview

This GitHub contains the Star Tracker (ST) development for SUCHAI 2 - 3. 
SUCHAI 1 is the first NanoSatellite developed by Universidad de Chile, at the 
Space and Planetary Exploration Laboratory (SPEL). Launched on June 23 (2017), 
the satellite is currently operational. Actually, we are working on two more NanoSatellites, the SUCHAI 2 & 3. <br />
[More info about the SUCHAI proyect.](http://spel.ing.uchile.cl)

## Description

- This is a fully functional Star Tracker for use with a Raspberry Pi and its camera. <br />
- This code is written in _Python_. All the code and the necessary files are in the __RPI__ folder. <br />
- This Git-Hub is __free__ and __open__ to everyone interested in using it, __especially researchers working on CubeSats!__. <br />

## Instructions for use

1. This ST code is based on two open softwares usually used in Astronomy: __Source Extractor__ and __Match__. In order to use this program, you need to install this two software first.<br />
    1.1.- Get and install [Source Extractor.](https://www.astromatic.net/software/sextractor) 
You can find this program in the RPI repository, and install it typing: <br />
        _sudo apt-get install sextractor_ <br />
We use __version 2.19.5__ in our program. <br />
    1.2.- Get and install [Match](http://spiff.rit.edu/match/). We use __version 0.14__ in our program. <br />

2. Clone this repository in any folder on your RPI, for example: __/home/pi/Desktop/Git/ST/__

3. Run in _Python_ the file _StarTracker_10deg.py_ . By default, it will use a picture from __/RPI/Sample_Images/__. Also, you can test it with other pictures, or use your own pictures taked with your RPI Camera.

## Any questions?

Contact: Samuel Gutiérrez Russell. <br />
PhD student in Electrical Engineering at Universidad de Chile, Santiago, Chile. <br />
e-mail: samuel.gutierrez@ug.uchile.cl
