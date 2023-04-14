# ROS-RVIZ-chess
This repository creates a playable chess game in RVIZ using ROS. It labels each piece in a chess game, sets the color to black or white, and enables the user to drag a piece into a new square in the 8 by 8 board. Also, the pieces snap into the middle of the new square after being moved.

After cloning the repository, put it in your Catkin workspace. To run the program you will need three terminal windows:
1) Run "roscore"
2) Run "rviz"
3) Run "rosrun my_markers chess_game.py
