# eece5550_slambreros
Follow the setup here: 

https://github.com/husarion/rosbot_description

Run the `./install` sh script

Install https://github.com/hasauino/rrt_exploration

In your catkin worksapce run:

`source devel/setup.sh`

`roslaunch multi_rosbot_launch rrt_multi.launch`

Wait until the rviz map loads. Then using the publish point feature on Rviz place 4 points in a square starting from the top-left corner and continuing counter-clockwise. Then place a 5th point on/between the robot(s) in the map.



