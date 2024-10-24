## Robotics Final Project of Group 2

To start the simulation, run the commands:
```
roslaunch locobot_simulation simulation_project_allobjects.launch
rosrun locobot_simulation auto_move_to_object.py
rosrun locobot_simulation arm_teleoperation.py
```

The Python file auto_move_to_object.py processes the data from image recognition publisher and aligns the robot base to face the object which we want to pick up, move it closer to it and stop it at the point to pick up the small blue ball.

Using the other script arm_teleoperation.py, it is possible by pressing 't' to move the robot arm into the position to pick up the object. The buttons 'o' and 'p' will open and close the gripper and 'r' will move it to the initial position.

The file main.py was used to focus the camera on a specific object, but in the end it is not used together with auto_move_to_object.py.


