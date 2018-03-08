# FireNIce

[![Build Status](https://travis-ci.org/frags51/FireNIce.svg?branch=master)](https://travis-ci.org/frags51/FireNIce)

A game in C++ to learn about concurrency. A part of PoPL-2 course.

## Contributing
Make all major changes to a new branch, and then open a pull request from that branch to master.

## Dependencies
Need SFML 2.4.2 
Download all the required packages for Ubuntu from http://ftp.sjtu.edu.cn/ubuntu/pool/universe/libs/libsfml/ and install via dpkg, since 2.4.2 is not available via the official repo on Ubuntu 16.04 and below.

Alternatively, run the following commands to build SFML:
     - sudo apt-get install libx11-dev freeglut3-dev libjpeg-dev libfreetype6-dev libxrandr-dev libglew-dev libsndfile1-dev     libopenal-dev libudev-dev
    - mkdir sf
    - cd sf
    - git clone https://github.com/SFML/SFML.git
    - cd SFML
    - cmake -G "Unix Makefiles" -D CMAKE_BUILD_TYPE=Debug -D BUILD_SHARED_LIBS=TRUE .
    - make
    - sudo make install
    - cmake -G "Unix Makefiles" -D CMAKE_BUILD_TYPE=Debug -D BUILD_SHARED_LIBS=FALSE .
    - make
    - sudo make install
    - cmake -G "Unix Makefiles" -D CMAKE_BUILD_TYPE=Release -D BUILD_SHARED_LIBS=TRUE .
    - make
    - sudo make install
    - cmake -G "Unix Makefiles" -D CMAKE_BUILD_TYPE=Release -D BUILD_SHARED_LIBS=FALSE .
    - make
    - sudo make install
    
    ## Installation
    To install the game, type cmake CMakeLists.txt in the source directory.
