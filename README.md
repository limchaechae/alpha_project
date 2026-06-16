실행 방법
터미널 1: roscore
터미널 2: rosbridge
source ~/catkin_ws/devel/setup.bash
roslaunch rosbridge_server rosbridge_websocket.launch
터미널 3: 
source ~/catkin_ws/devel/setup.bash
roslaunch alpha_control parking_morai_fixed.launch ctrl_topic:=/ctrl_cmd_0 ctrl_topic_secondary:=/ctrl_cmd
test 시나리오도 업로드함
