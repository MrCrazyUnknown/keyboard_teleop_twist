# keyboard_teleop_twist
---_Made by: Suyash Verma (MrCrazyUnknown)_
## Classic WASD controls for/in ROS


This package is meant for controlling a robot(ROS) (on ground) using keyboard

---
### Features:

- It supports _classic **WASD**_ controls (ROS kinetic/melodic/noetic).

- **_W/S_** are for _moving_ **forwards** & **backwards** respectively

- **_A/D_** are for ~~moving~~ _rotating_ **left** and **right** respectively

- **_T/G_** are for **increasing** and **decreasing** _linear_ speed respectively

- **_Y/H_** are for **increasing** and **decreasing** _angular_ speed respectively

---


### Usage:

- First install the package:
    ```linux shell
    cd <workspace>/src
    git clone https://github.com/MrCrazyUnknown/keyboard_teleop_twist.git
    ```
    
- Next use it: (Only after launching your Gazebo world) (The robot to be controlled should subscribe to /cmd_vel (twist))
    ```linux shell
    rosrun keyboard_twist_teleop teleop.py
    ```
---
