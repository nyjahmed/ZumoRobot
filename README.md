# ZumoRobot
Zumo Robot Maze Solver

To complete this project I used tutorials on Professor deLeeuw's GitHub, example LineSolver code provided with the Zumo Robot, and online documentation. In the video, the robot solves the maze pretty well, except that it misses a left hand turn towards the end. I believe this is because there was a bump in the tape at that point so the Zumo sensors were having a tough time detecting the turn. I attempted to optimize the solution by maxing the speed the Zumo went at. Unfortunately, this would cause the Zumo to go too fast and miss some key left turns it should have detected. I tried to create stops if the Zumo detected a left line to give the Zumo time to turn left. In the end, this solution worked and the Zumo was detecting lines it was previously missing, however the overall time only decreased by 2 seconds. 

