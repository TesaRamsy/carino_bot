## Robot Package Template

## To clone package for diffdrive_arduino :
 git clone https://github.com/Buzzology/diffdrive_arduino.git
  
## for ros2_humble go to diffdrive_arduino directory and run this : 
  git checkout 3883c0
## for serial
  git clone git clone https://github.com/joshnewans/serial

## for rplidar ld20(same with ld14p)
  git clone https://github.com/ldrobotSensorTeam/ldlidar_sl_ros2.git

## FOR SIMULATION AND CONTROLLER
  sudo apt install -y ros-humble-gazebo-ros* 
  sudo apt install -y ros-humble-ros2-control*
  sudo apt install -y ros-humble-controller-*

## FOR NAV . SLAM-TOOLBOX
  sudo apt install ros-humble-navigation2
  sudo apt install ros-humble-nav2-bringup
  sudo apt install ros-humble-turtlebot3*
  sudo apt install ros-humble-twist-mux ros-humble-nav2*     
  sudo apt install ros-humble-robot-localization
  sudo apt install -y ros-humble-slam-toolbox

## FOR JOYSTICK
  sudo apt install ros-humble-joy*
  sudo apt install joystick jstest-gtk evtest -y
