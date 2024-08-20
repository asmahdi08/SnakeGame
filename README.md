# Snake Game in C++

## Introduction
This project is a version of the classical snake game developed in C++, and its STL.

## Libraries and tools
- STL
- [Conio.h](https://bit.ly/2yTfPUe)

## Colours
To print coloured chars and change the background colour, I used the [ANSI escape code](https://bit.ly/3euJ1R5) I preferred to do such implementation to use a native function of Windows and C++, instead of import a external library,  making the final program a bit shorter.

 Moreover, its colour range fitted to the necessity of my project, and the scape code was an easy tool, the only thing I had to do was print my code in this format:

```cpp
cout << COLOUR_CODE << "Text" << RESET_COLOR_SCHEME;
```

## Compilation
If you wish to compile the code and run it on your computer, you need to use the following terminal command:
```cmd
g++ -std=c++17 -O2 Header.hpp Source.cpp Snake.cpp Main.cpp -o snake_game
```

## Observations
* This code uses the library ```<Windows.h>```, that only works on Windows platform.

or you could use mingw on other platforms to compile 


Arcade 27
