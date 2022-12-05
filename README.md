# Sudoku

![image](https://user-images.githubusercontent.com/67956852/205489007-207d6c4b-88e6-46e8-97ea-f23f08a1087c.png)

# About Sudoku
This is a simple Sudoku Puzzle game made with `C++` and `Qt5`. Qt's framework & tools are the smarter way to build & deploy software, design UIs & develop applications across all platforms.

Sudoku is a logic-based placement puzzle. Although an early variant of the puzzle waspublished in a French newspaper in 1895, modern interest in Sudoku stems from a revival in Japan in 1986, leading to widespread international popularity in 2005.

In sudoku puzzles, the goal is to write one number in each empty cell, so that each column, row, and region contains the numbers 1–9 exactly once. Obviously, these values can be correct or wrong. When all values in white cells are correct, the system knows that the sudoku is finished.

The algorithm used for solving sudoku via computer is backtracking. This method is a depth-first search and tests a whole branch of until this branch violates the rules or this branch is the solution. For every unassigned index, there are 9 possible options so the time complexity of the solution is O(9<sup>n<sup>2</sup></sup>).
 
 # Dependencies
 Install the following dependencies
 ```
apt update && apt upgrade
apt install libqt5svg5-dev g++ gcc make cmake
apt-get install qttools5-dev
apt install qtcreator qtbase5-dev qt5-qmake
 ```
  

# Build and Run
Create a build folder and build it using `CMake`
```
mkdir -p build
cd build
cmake ..
make
./sudoku
 ```
    
   



