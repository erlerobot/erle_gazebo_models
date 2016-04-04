## About
Aruco marker model for testing [ros_erle_pattern_follower](https://github.com/erlerobot/ros_erle_pattern_follower) in Gazebo.

## How to use it
- Download and compile [this plugin](https://github.com/erlerobot/ardupilot_sitl_gazebo_plugin/tree/master/aruco_mark_plugin) by following [these instructions](https://github.com/erlerobot/ardupilot_sitl_gazebo_plugin/tree/master/aruco_mark_plugin/README.md).
- In `model.sdf`: replace `circle` with either `square` or `dot` (inside `<shape></shape>` tags) depending on what shape you want the mark to follow.

## Applications
Watch what this is useful for [here](http://erlerobotics.com/docs/Simulation/Vehicles/Erle-Copter/Tutorial_5_Pattern_follower.html).
