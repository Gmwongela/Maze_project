The Maze
The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

About SDL2
Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

AUTHOR
Gideon Mwongela


Keyboard Keys for Players
Arrow Keys -- Player Directions
R -- Refresh
M -- Map
C -- Zoom Player view
[ -- Zoom Out in Game
] -- Zoom In in Game
F -- Change Views (Normal view to Panoramic view and vice versa)
T -- Change Texture of walls and square columns
Tools and Languages Used...
C language
SDL2 (Simple Directmedia Layer)
Ray-Casting
Bash
Compiling
Using a Windows Operating sysytem, Navigate to the src folder and Compile with gcc -std=c17 *.c -I{Path to SDL2\include} -L{Path to SDL2\lib} -Wall -lmingw32 -lSDL2main -lSDL2 -o raycaster Check out this link for help.

Using Linux, Navigate to the src folder and Compile with gcc -o raycaster *.c 'sdl2-config --cflags --libs' -lm

Remove the line #define SDL_MAIN_HANDLED from the source codes in Linux


The Maze Project MVP flowchart
https://lucid.app/lucidspark/f0d4852d-d717-498d-bb16-666012e0b1e4/edit?viewport_loc=-171%2C-42%2C2763%2C1313%2C0_0&invitationId=inv_26b68f66-9705-4590-ae89-a9c6c18dd341

