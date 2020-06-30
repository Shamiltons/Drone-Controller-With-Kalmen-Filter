# Drone Controller with estimator

## Description

Controller uses cascading PID controllers to control a quad copter
Controller assumes a gaussian distribution for the noise on sensor readings,
It uses GPS, and 9 axis gyroscopes with an altitude sensor to control the drone.
All the sensor data is filter using an Extended Kalmen Filter, In the future I intend
to switch to an unscented Kalmen Filter.

## Installation

1) Download
2) create build dir
3) run cmake .. then cmake

System is designed to run on a linux distro on a drone but can be used on Window
or desktops with a simulator like Ardupilot.
