# MazeSolver
A Maze Solver Mobile Robot Based on StateMachine (smash library)
## Installation
Add the mobile_robot_description package to your workspace then build it using

```bash 
catkin_make
```
and add the models to .gazebo folder in your home directory.

## Running

```bash
roslaunch mobile_robot_description maze_runner.launch
```

```bash
rosrun smach_viewer smach_viewer.py
```

```bash
rosrun mobile_robot_description wall_follower_super_simple.py
```
