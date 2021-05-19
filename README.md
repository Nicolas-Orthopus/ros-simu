# ros-simu

TODO : 
Document this file  

# visualize URDF model with RViz (to debug it)

- clone the repo in your catkin_ws/src  
- use catkin_make  
- launch rviz with  : roslaunch robot_description display.launch   

# open the simulation with Gazebo and control the joints with RQT

- launch the gazebo environment with : roslaunch robot_gazebo robot.launch
- launch the controllers with : roslaunch robot_control jaco_control.launch
- Run RQT with : rosrun rqt_gui rqt_gui 
- Now in the RQT interface go to Plugin->Topic->Message Publisher
- Add the joints you want to control, and set the rate if needed 
- Add the actuator's position equation in data
