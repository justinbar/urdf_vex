# vex_robot-URDF
this project is to be use with ros2
# create a new directory such as 
$ mkdir -p robot_ws
# now clone my file by using 
$ git clone https://github.com/justinbar/urdf_vex.git 
 change my folder name "urdf_vex" to "vex_robot"
# use the colcon build tool to compile our files
$ colcon build
# now is time to launch vex robot on to gazebo 
$ ros2 launch vex_robot launch_sim.launch.py
# we can control our robot with keyboard (optional test)
$ ros2 run teleop_twist_keyboard teleop_twist_keyboard


