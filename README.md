# Vitulus teleop
 Keyboard teleop for VITULUS.

Node [/vitulus_teleop_keyboard]

Publications: 
 * /cmd_vel [geometry_msgs/Twist]

   Desired speed of the robot in m/s.

 * /rosout [rosgraph_msgs/Log]

## Install

`cd ~/catkin_ws/src/vitulus`

`git clone https://github.com/lacina-dev/vitulus_teleop.git`

`cd ~/catkin_ws`

`catkin build`

## Run

`roslaunch vitulus_teleop vitulus_teleop_key.launch`

 More about VITULUS? See my website.
 [https://lacina.dev](https://lacina.dev)

 Questions? Try Discord.
 [Discord channel](https://discord.gg/YqeNV5hEVN)