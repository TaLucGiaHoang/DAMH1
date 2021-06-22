The code used in this project was copied from boneCV repository of Derek Molloy.
Thank you for your teaching and sharing.

#Author
Derek Molloy: 
- Tutorial: http://derekmolloy.ie/streaming-video-using-rtp-on-the-beaglebone-black/
- Github: https://github.com/derekmolloy/boneCV
Copyright Derek Molloy, School of Electronic Engineering, Dublin City University

#To clone this repository 
    git clone git://github.com/derekmolloy/boneCV
    
#To build source files
##Building the Video4Linux frame capture program
    gcc -O2 -Wall `pkg-config --cflags --libs libv4l2` grabber.c -o grabber

##Building the Video4Linux capture example program
    gcc -O2 -Wall `pkg-config --cflags --libs libv4l2` capture.c -o capture
