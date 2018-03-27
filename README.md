# ros_repository
Laboratorio Ciberfisico UniVR

## Getting Started

### Prerequisites

You need [ROS Kinetic](http://wiki.ros.org/kinetic/Installation) installed and working

### Try it

You can try it by calling on a terminal

```
roscore
```
and on three terminals run

note: hello_ros is the package's name in this case


```
rosrun hello_ros talker.cpp
```

```
rosrun hello_ros listener.cpp
```

```
rosrun hello_ros ten.cpp
```

You will se that all the packages sended by 'talker' are seen by 'listener'. Every 10 packages received, listener  will send a message to ten.

## License

This file is part of hello_ros and it is distributed under the terms of the GNU Lesser General Public License (Lesser GPL)

## References

***Laboratorio Ciberfisico*** <br >
Robot Programming with ROS <br >
A.Y. 2017/2018 <br >
University of Verona (Italy)
