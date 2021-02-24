# CHIP-8-Emulator
A CHIP-8 emulator implemented in C

![Space Invaders](screenshot/invaders.png "Space Invaders")

*Space Invaders*

![Pong](screenshot/pong.png "Pong")
*Pong*

(screenshot/brix.png "Pong")
*Brix*


## Compiling and Running

Requires cmake and SDL2:
```
$ sudo apt-get install cmake libsdl2-dev
```

Compile:
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```

Run:
```
./chip8 <ROM file>
```
23 (public domain) ROMs are included in the `roms` directory.

## References
Some helpful resources I used when writing this

- http://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/
- http://en.wikipedia.org/wiki/CHIP-8
