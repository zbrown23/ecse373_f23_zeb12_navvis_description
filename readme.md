## navvis_description

This package contains the robot description for the navvis platform. It can be displayed in rviz and  launched with the following:

```roslaunch navvis_description display.launch```

the launch file takes the following arguments:
* use_xacro - a boolean that specifies whether to use the URDF or xacro version of the robot
* file - a path to be passed in order to override the default robot description
* use_joint_state_publisher_gui - a boolean that indicates whether the gui joint state publisher should be opened and turned on.
