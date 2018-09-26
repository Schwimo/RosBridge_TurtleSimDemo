# Turtlesim via Rosbridge 2.0 and Python
A small demo on how to control the turtle simulation with a python rosbridge implementation.

### SERVER

#### Install ROS Kinetic or the version you want
[ROS Kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu)

#### Install ROS BRIDGE
[ROS Bridge](http://wiki.ros.org/rosbridge_suite/Tutorials/RunningRosbridge)

#### Install Turtlesim
[Turtlesim](http://wiki.ros.org/turtlesim)


### CLIENT

#### Setup
To run the demo you have to install ws4py and json.
pip install ws4py
pip install json

Adjust the IP you want to connect to on line 62.
```python
...
client = RosBridgeClient('ws://192.168.4.68:9090/')
...
```

#### Start
Just run the demo.py and you should see the turtle moving.

### Helpers
[ROS Bridge Wiki](https://github.com/RobotWebTools/rosbridge_suite/blob/develop/ROSBRIDGE_PROTOCOL.md)
Here you see all possible command to initialize all kind of interaction.
