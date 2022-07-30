# Install Arm package
### Install Arm package task 3 for  AI at SmartMethods summer training

1- create folder <br />
`mkdir -p ~/catkin_ws/src`

`cd ~/catkin_ws/`

`catkin_make`

2- Insall arm package

`cd ~/catkin_ws/src`


`git clone https://github.com/smart-methods/arduino_robot_arm.git`

`cd ~/catkin_ws`

`rosdep install --from-paths src --ignore-src -r -y`

`sudo apt-get install ros-noetic-moveit`

`sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui`

`sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher`

`sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control`

`sudo nano ~/.bashrc`

3- At the end of the "bashrc" file, add the following line: 

Location : (source /home/tariq/catkin_ws/devel/setup.bash) 
then to write out 
 ctrl + o
and to ext ctrl + x

4- updeat the source<br />
`source ~/.bashrc`

5- now run the Rviz<br />
`roslaunch robot_arm_pkg check_motors.launch`
