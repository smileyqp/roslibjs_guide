> ##### terminal中同时打开：
> 注意：请提前安装ros以及rosbridge_server等
```shell
roscore

rostopic pub /listener std_msgs/String "Hello, World"

rostopic echo /cmd_vel

rosrun rospy_tutorials add_two_ints_server

roslaunch rosbridge_server rosbridge_websocket.launch
```
