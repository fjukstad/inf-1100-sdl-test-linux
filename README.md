# inf-1100-sdl-test-linux

A simple test to check that SDL and compilers has been installed correctly on Linux. For the students of  INF-1100 fall 2013

# Howto
Download, make and run

# Problems
Ubuntu users may need to modify line 16 in the Makefile to something like
this: 
    
    gcc -Wall -o $@ -Iinclude $(SOURCE) $(SDL_LIB)

if it doesn't compile. 
