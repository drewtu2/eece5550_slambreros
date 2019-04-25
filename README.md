Run the 

Clone this repo to the source directory of your catkin workspace.

```
./install.sh
```
Change to your catkin workspace src directory and run
```
git clone https://github.com/hasauino/rrt_exploration
```
to get the `rrt_exploration` package.

In your catkin worksapce run:

```
source devel/setup.sh
roslaunch multi_rosbot_launch rrt_multi.launch
```

Wait until the rviz map loads. Then using the publish point feature on Rviz 
place 4 points in a square starting from the top-left corner and continuing 
counter-clockwise. Then place a 5th point on/between the robot(s) in the map.
