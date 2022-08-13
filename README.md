# Raylib base

A starter application for a raylib project, complete with a .vscode directory and a makefile.

This project is meant to be used for vs code and C++

## Instructions for use

Note this repository is based on [BarjiLIVE's tutorial](https://www.youtube.com/watch?v=u6LXRF-iMg8) so this instructions will only detail what BarjiLIVE did on said video, I recommend watching that video instead of 
following these instructions.

1. clone [the raylib repository](https://github.com/raysan5/raylib).

2. Next, compile said repository by running mingw32-make on the src/ directory.
(you will need to have mingw32 installed)

3. clone this project into your computer (and delete the .git folder)

4. copy the raylib.h file from raylib/src into this project's include folder

5. copy the libraylib.a file from raylib/src into this project's lib folder

6. run the application by pressing f5 on vs code or running mingw32-make on the
project directory.