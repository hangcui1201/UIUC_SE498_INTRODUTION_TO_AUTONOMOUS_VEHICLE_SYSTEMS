### JACKAL_ROBOT_SIMULATION

[//]: # (Image References)

[image1]: ./demo_images/gazebo_demo.png "Gazebo"
[image2]: ./demo_images/rviz_demo.png "Rviz"

### Put all folders in the src folder of a catkin workspace, i.e. catkin_ws/src

$ cp JACKAL_ROBOT_SIMULATION/* ~/catkin_ws/src  
$ cd ~/catkin_ws && catkin_make

### Terminal 1
$ source devel/setup.bash  
$ roslaunch jackal_drive jackal_drive.launch

### Terminal 2
$ source devel/setup.bash  
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py  

### Gazebo
![alt text][image1]

### Rviz
![alt text][image2]

