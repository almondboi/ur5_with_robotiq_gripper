# ur5e_with_robotiq_gripper

## Installation

Run the installer to install dependencies on kinetic:
	
	./installdep
This will also create a new workspace called:
	ur5e_gripper_ws

Next up, build your workspace

	cd ur5e_gripper_ws
	catkin_make

## Dependencies

universal_robot
Universal_Robots_ROS_Driver
robotiq
roboticsgroup_gazebo_plugins
ros_controllers

Usage with Gazebo 

To launch jog_control:

```roslaunch icl_ur5_setup_gazebo ur5e_gripper.launch``` 

This will launch Gazebo, moveit! planner, rViz and launch jog_control for the ur5e.

