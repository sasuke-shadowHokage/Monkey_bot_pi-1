# Monkey-Bot-PI
 This package for should install in raspberry pi
 ### step 1
 create a workspace on your pi
 ```sh
 $ mkdir -p ~/Monkey_Bot_Pi/src
 $ cd Monkey_Bot_pi
 $ catkin_make
 $ cd
 ```
 ### step 2
 Source the workspace to your raspberry pi
 follow the command
 ```sh
 $ nano .bashrc
 "got to last if the contains any data paste below command. if does not have any data type "cd" in terminal then type above code"

 source /home/sasuke/monkey_bot_pi/devel/setup.bash
 $ source .bashrc
 ```
 ### step 3
  To activate the rosserial follow the command
  ```sh
  rosrun rosserial_python serial_node.py _port:=/dev/ttyACM0 _baud:=9600
  ```
  ### step 4
  To activate the Lidar scan data
  follow this command
  ```sh
  $ roslaunch ydlidar_ros X2.launch
  ```
  ### step 5
   Follow this link for next procedure
   ```sh
   https://github.com/sasuke-shadowHokage/Monkey_Bot/tree/main
   ```
  
 
  
 
 
