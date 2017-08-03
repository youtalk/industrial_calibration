industrial_calibration
======================

Contains libraries/algorithms for calibration industrial systems

# Travis CI

[![Travis-CI](https://api.travis-ci.org/ros-industrial/industrial_calibration.svg?branch=indigo-devel)](https://travis-ci.org/ros-industrial/industrial_calibration/branches) 

# Examples
## Single Basler on a rail
```
roslaunch robocyl_ical.launch
roslaunch robo_cylinder.launch
rosservice call /RobocylCalService "allowable_cost_per_observation: 0.25"
```
