# The-great-Maze-project
 The Maze is an immersive 3D puzzle escape game, which is designed to challenge players’ critical thinking and
 problem solving skills through intricate navigation and problem solving skills.
 The Maze is targeted at puzzle enthusiasts aged 12 and above, the game aims at providing a unique and
 engaging experience by utilizing advance SDL2 and raycasting technologies to create a visually stunning and dynamic environment.


[LinkedIn profile](https://www.linkedin.com/in/oussama-chennak/)

# Installation

Here's a step by step guide on installing the Maze game on your system.

## Prerequisites
1) SDL2: Make sure you have SDL2 installed on your system
2) Compiler: Make sure you have a C compiler installed (eg., GCC for Linux, MINGW for windows, Xcode for MacOS)

## Steps
1) Begin by cloning the repository from GitHub to your Local machine
```
git clone https://github.com/Lamba237/The-great-Maze-project.git
```

2) Install the SDL2 Library on your system
* On Ubuntu 20.04
```
sudo apt-get install libsdl2-dev
```
* On MacOS
```
brew install sdl2
```
## Usage
1) Enter into the github directory on your local machine
```
cd The_Maze
```
2) Compile using the C compiler
```
gcc -std=c99 ./src/*.c -lSDL2 -lm -o raycast
```
3) Run your application after you've compiled
```
.\raycast
```
![image](https://github.com/Lamba237/The-great-Maze-project/assets/129569062/db04ce59-c054-45d9-91dd-006850c7e643)
## Contributing
[Oussama Chennak's Github](https://github.com/Oussamachennak123)
## References
[SDL2-Get started.pdf](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/misc/2021/1/9da3b82dc0bcfea07858b70956de47f0e2db2dad.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240710%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240710T210323Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3ecf88c296e2c5402de6eda885c7a588f88db55d347982423ac86699901a459a)

[SDL2 tutorials](https://lazyfoo.net/tutorials/SDL/index.php)

[Raycasting beginners guide](https://permadi.com/1996/05/ray-casting-tutorial-table-of-contents/)

[Alternative Raycasting Tutorial](https://lodev.org/cgtutor/raycasting.html)
