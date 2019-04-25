

# References:

## Husarion specfic: 
- [Husarion Multiple Machines](https://husarion.com/tutorials/ros-tutorials/5-running-ros-on-multiple-machines/)
- [Husarion SLAM](https://husarion.com/tutorials/ros-tutorials/6-slam-navigation/)
- [Huasarion Path Planning](https://husarion.com/tutorials/ros-tutorials/7-path-planning/)
- [Husarion rosbot description](https://github.com/husarion/rosbot_description)
- remapping the rosserial requires passing arguments in directly to their executable: 
`/opt/husarion/tools/rpi-linux/ros-core2-client /dev/ttyCORE2 __name:=serial_node_2 cmd_vel:=cmd_vel_2 rangeL:=rangeL_2 rangeR:=rangeR_2 pose:=pose_2`


## Nav Stack Specific
- [Navigation Stack](http://wiki.ros.org/navigation)
- [Navigation Tutorial Stack](http://wiki.ros.org/navigation/Tutorials/RobotSetup)
- [2D cost maps](http://wiki.ros.org/costmap_2d)

## tf
- [tf](http://wiki.ros.org/tf)
- [tf multiplerobots](https://answers.ros.org/question/246338/how-to-connect-tf-for-multiple-robots-in-slam/)
- [tf2 depreicates prefix](http://wiki.ros.org/tf2/Migration)
- essentially, the `tf_prefix` is not really supported since most packages failed
to implement it correctly to begin with. As a result, if you're relying on `tf_prefix`
to correctly namespace your `tf frames`, you will have a bad time. Trust us. 
Been there. Done that. 

## Beyond the Nav Stack
- [SLAM gampping](http://wiki.ros.org/gmapping?distro=hydro)
- [Multi Map Merge](http://wiki.ros.org/multirobot_map_merge)
- [Explore Lite](http://wiki.ros.org/explore_lite)
- [Emerson Boyd - EECE5698](http://emersonboyd.com/projects/multi-agent-slam)
- [Multi Robot SLAM](https://answers.ros.org/question/41433/multiple-robots-simulation-and-navigation/)
