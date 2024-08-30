# akros2_msgs
![](https://img.shields.io/badge/ROS%202%20Galactic-Ubuntu%2020.04-blue) ![](https://img.shields.io/badge/ROS%202%20Humble-Ubuntu%2022.04-blue) ![](https://img.shields.io/badge/ROS%202%20Jazzy-Ubuntu%2024.04-blue) ![GitHub License](https://img.shields.io/github/license/adityakamath/akros2_msgs)
 ![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/kamathsblog)
 
Custom messages for the AKROS2 robot

## Mode.msg
Data type with two booleans, which show the status of the emergency stop (e-stop) and the autonomous mode (autonomous mode when True, teleop mode when False) respectively.

```
bool estop
bool auto_t
```
