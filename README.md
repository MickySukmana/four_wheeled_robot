# four_wheeled_robot
Simulation of a four wheeled robot using ROS2 and Gazebo

This project used two libgazebo_ros_diff_drive plugin for the front and rear wheel instead of libgazebo_ros_skid_steer_drive plugin, cause currently i can't get the plugin to works.  

to run the simulation use this command below
```
ros2 launch four_wheeled_robot launch_sim.launch.py
```
you can control the robot by using teleop package.
```
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```
