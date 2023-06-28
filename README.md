# can_picking_robot

##Requirements:
>Ubuntu 22.04 LTS
>ROS-Humble
>Gazebo (for simulation)
>Moveit Assistant (to control the joints of the robot)
>Rviz2
>Tensorflow & Keras


A demo of how the robot looks like and operates

[one.webm](https://github.com/unknown-entity98/can_picking_robot/assets/97030480/792b42ea-01bf-4f91-96c1-9db4b3762f48)

##Objective:
The objective of this robot is to be able to detect if there is any coca-cola can in front of it, and move towards it accordingly. After moving near it, the joints bend so that the gripper can pick the can up and the can should then be taken. 
However the task is quite complex since the robot not only has to navigate, but also control the joints after detecting the distance from the object and pick it up. 

##Future Work
The model can be run in a better way and we can try including more packages if we wish to give the robot more functionalities.
