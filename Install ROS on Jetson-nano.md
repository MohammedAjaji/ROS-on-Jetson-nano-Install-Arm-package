
# Install ROS on Jetson-nano
### Install ROS on Jetson nano  task 2 for AI at SmartMethods summer training

1- Open a new terminal

2- Set up the Jetson Nano to accept software from packages.ros.org <br />
`$ sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'`

3- Add a new apt key:<br />

`$ sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654`

4- Update the Debian packages index:<br />

`$ sudo apt update`

5- Install the ROS Desktop package :<br />

`$ sudo apt install ros-melodic-desktop`

6- load the ROS environment variables automatically when you execute a new shell session<br />

`$ echo "source /opt/ros/melodic/setup.bash" >> ~/.bashrc`
`$ source ~/.bashrc`

7- Install and initialize rosdep :<br />

`$ sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential`<br />
`$ sudo rosdep init`<br />
`$ rosdep update`<br />
#### Now the Jetson Nano is ready to execute ROS packages
