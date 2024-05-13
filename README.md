# ROS-RVIZ-chess
ROS-RVIZ-chess is a playable chess game in RViz using ROS. It labels each piece in a chess game, sets the color to black or white, and enables the user to drag a piece into a new square in the 8 by 8 board. Also, the pieces snap into the middle of the new square after being moved.

After cloning the repository, put it in your Catkin workspace. To run the program you will need three terminal windows:
1) Run "roscore"
2) Run "rosrun my_markers chess_game.py"
3) Run "rviz"

In the RViz window, perform these four actions:
1) Under "Global Options" in "Fixed Frame," change "map" to "base_link"
2) Under "Grid," change "Plane Cell Count" to 8
3) Click "add" in the lower left corner and select "InteractiveMarkers"
4) Under "InteractiveMarkers," change "Update Topic" to "/basic_controls/update"

You should now see the pieces appear in the chess board, which is ready to be played. See the video below for an example of the beginning of a chess game using this simulation environment.

https://user-images.githubusercontent.com/71709732/232178960-5499c94d-5b01-4a6c-8492-d5e3ef137e3c.mov
