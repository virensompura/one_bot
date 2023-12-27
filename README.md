# ONE_BOT

## Linux Code to run the Robot

### Spawning the Robot in Gazebo 

    $ ros2 launch one_bot launch_sim.launch.py world:=<path_of_.world_file>

### Launch Robot 
    
    $ ros2 launch one_bot launch_robot.launch.py

### For Lidar 

    $ ros2 launch one_bot rplidar.launch.py

### Teleop Twist Keyboard

    $ ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_cont/cmd_vel_unstamped

### For Cartographer Mapping 

    $ ros2 launch one_bot cartographer.launch.py

### For Navigation 

    $ ros2 launch one_bot navigation.launch.py
    

