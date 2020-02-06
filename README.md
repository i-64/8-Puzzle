# N Puzzle / 8 Puzzle
  This is my C++ implementation for solving generalised 8 puzzle, i.e., N-puzzle using A-star search algorithm. For SPPU's BE practical assignment in Artificial Intelligence and Robotics (AIR) course.

## Instructions to run

  ### 1. Compile C++ code:
  
    $ g++ main.cpp
  
  ### 2. Run code:
  
    (a) Linux:
    
      $ ./a.out
      
    (b) Windows:
    
      $ a.exe

## Changing the input
  The code reads input from the file "in.txt".
  Input Format:
    
    2 8 3
    1 6 4
    7 0 5
    
    1 2 3
    8 0 4
    7 6 5
   The first n lines contain the initial state, last n lines contain the goal state.

## Changing the size of board/grid
  The code assumes the board size to be 3x3.
  It can be changed to another integer >= 2 by changing the value of n in "line #2 in main.cpp"
