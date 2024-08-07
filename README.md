# VR-Robot-Control
## Launching robot side nodes
1. create ros workspace and clone this repository in src folder then build workspace.
2. roslaunch ros_tcp_endpoint endpoint.launch
3. roslaunch ros_tcp_endpoint endpoint.launch
### Topics published from virtual reality headset
3. rostopic echo /vr_right_controller_pose
4. rostopic echo /vr_headset_pose 
5. rostopic echo /vr_left_controller_pose 
### Node to publish color message subscribed by the vr headset
6. rosrun unity_robotics_demo color_publisher.py 
### Node graphs/topics/plots
7. rqt_plot 
8. rqt_topic 
9. rqt_graph
