# Digital-Twin-for-UR5-Robot
Digital Twin for UR5 robot with MATLAB

## MATLAB ##
UR5_Connection.mlx is a Live script MATLAB file. There are separated sections for running the code step by step.

## ROS ##

1. Create catkin workspace before extract the file that I uploaded. To create catkin workspace is https://wiki.ros.org/catkin/Tutorials/create_a_workspace. (Melodic)

2. After create catkin workspace, extract <folder_name>.tar.xz file into the <folder_name> (Ex. build.tar.xz -> extract to build folder in your catkin workspace)

3. In src folder in your catkin workspace, you must create git clone by following this code:

$ cd ~/<your_catkin_workspace_name>/src

$ git clone -b melodic-devel https://github.com/ros-industrial/universal_robot.git src/universal_robot 
