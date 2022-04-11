# A 2-Wheeled Robot

## Description:

#### This project is made for exploring **[Robot Operating System (ROS)](https://www.ros.org/)**. I have followed [The Construct](https://www.youtube.com/channel/UCt6Lag-vv25fTX3e11mVY1Q)'s _Exploring ROS using a 2 Wheeled Robot_ series.

-   The 2-wheeled robot is made using ROS Noetic on Ubuntu 20.04.
-   The structure is defined in Unified Robotic Description Format (URDF).
-   The visualization is run on RViz.
-   The simulation is run on Gazebo.

    ![two-wheeled-robot](./visuals/1-RViz.png 'RViz Simulation')

    ![two-wheeled-robot](./visuals/2-Gazebo.png 'Gazebo Simulation')

-   The robot is controlled using the [teleop_twist_keyboard](http://wiki.ros.org/teleop_twist_keyboard) package.

    ![two-wheeled-robot](./visuals/3-KeyboardControl.gif 'Keyboard Control')

-   The robot is mounted with a [laser scan sensor](http://gazebosim.org/tutorials?tut=ros_gzplugins#Laser).

    ![two-wheeled-robot](./visuals/4-LaserMount.png 'Laser Mount')

-   The laser detects objects in the robot's surroundings.

    ![two-wheeled-robot](./visuals/5-LaserScan.png 'Laser Scan')
