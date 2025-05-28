# Micro Rover Maze Solver 🤖  
**An Arduino-based robot that navigates mazes using A* algorithm.**  

## Features  
- 🚗 **Motor control** via I2C/PWM (`Freenove_Micro_Rover.py`).  
- 🧩 **Maze generation** (`Maze.py`) with start (S) and end (E) points.  
- ⚡ **A* pathfinding** (`Maze_Solving_Algorithm.py`) for optimal routes.  

## Hardware  
- Micro:bit or Arduino  
- Motor driver + ultrasonic sensor (для `get_distance()`).  

## Usage  
1. Upload code to the rover.  
2. Run maze solver to get path coordinates.  
3. Rover follows the path autonomously! 
