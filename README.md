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
you can switch between low resolution and high resolution model by commenting either robot_core_lr.xacro or robot_core_hr.xacro in robot.urdf.xacro
![alt text](https://github.com/MickySukmana/four_wheeled_robot/blob/main/img/lr_model.png?raw=true)
![alt text](https://github.com/MickySukmana/four_wheeled_robot/blob/main/img/hr_model.png?raw=true)
