# VR-Robot-Control
## Launching robot side nodes
1. Open and source unity_ws
roslaunch ros_tcp_endpoint endpoint.launch
rostopic echo /vr_right_controller_pose
rostopic echo /vr_headset_pose
rostopic echo /vr_left_controller_pose
rosrun unity_robotics_demo color_publisher.py
Rqt_plot
Rqt_topic
rqt_graph
