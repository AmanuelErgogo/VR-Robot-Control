# VR-Robot-Control
## Launching robot side nodes
1. Open and source unity_ws
2. roslaunch ros_tcp_endpoint endpoint.launch
3. rostopic echo /vr_right_controller_pose
4. rostopic echo /vr_headset_pose \
5. rostopic echo /vr_left_controller_pose \
6. rosrun unity_robotics_demo color_publisher.py \
7. rqt_plot \
8. rqt_topic \
9. rqt_graph \
