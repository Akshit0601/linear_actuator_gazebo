# linear_actuator_gazebo

after catkin_make:

1. To launch in gazebo(in terminal ): roslaunch linear_actuator3_description gazebo.launch <br/> 
launching controllers :
2. roslaunch linear_actuator3_description controller.launch

Controlling :
rostopic pub -1 /linear_actuator3/Slider2_position_controller/command std_msgs/Float64 "{data : 64}"

