Problem Statement:
Develop a multi-agent slam algorithm to quickly map out a room while avoiding collisions. This will involve managing the location and relation between multiple robots, as well as communicating data to and from a central server, which would store the global map. This will enable us to decrease the time to completely map an area, a potentially significant time savings for large rooms. Additionally, once mapped, these robots will be able to develop the same path given unique starting and end points.

Objectives: In addition to the standard project, our project will
1. Create a unified map based on data readings from N robots.
2. Update map readings in real time.
3. Maintain a central server to control N robots (reduces problem to multi-body mapping).

Requirements: In addition to the standard project, our
1. Robots will have the ability to communicate with a central server to send data about its environment.
2. The map will be created X times faster than a single robot would be capable of.
3. The robots shall explore in different directions, and minimize the amount of area visited more than once.
4. The robots will create a unified map, and resolve feature conflicts.
