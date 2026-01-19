# Universal Robots Dynamic Parameters ande Configurations
This repository serves as a community-supported source of dynamic parameters for Universal Robots. 

## How to read
Each UR robot is shipped with a base parameter configuration and then a calibrated offset. In this repository, we have included the base parameter configurations for a number of different UR robots. Important parameters such as rotor inertia and gear ratio allow users to calculate dynamic parameters of the robot that are hidden in most control systems. 

To calculate topics of interest such as reflected inertia, simply find the robot you are interested in `robot_configs`, then look up properties for each of the joints in `joint_configs`. 

## Contribute
Feel free to contribute to this community-based repository so we can all learn and grow the robotics community. 
