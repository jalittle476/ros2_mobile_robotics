# Section 01 – Publisher and Subscriber Nodes (Python & C++)

## What I Built

- A simple ROS 2 publisher and subscriber in Python (`rclpy`) and C++ (`rclcpp`)
- Each node published or received a `std_msgs/String` message on a topic

## What I Learned

- How to define a basic `Node` in both Python and C++
- The structure of a ROS 2 package (src, package.xml, setup.py or CMakeLists.txt)
- How to use `ros2 run` and `ros2 topic echo` to verify node communication
- How to use `ros2 topic list` and `ros2 topic info /{topic}` to check node publication
- C++ is more verbose, but gives more control and performance for real-time systems

## How I Ran It

ros2 run bumperbot_py_examples simple_publisher  
ros2 run bumperbot_py_examples simple_subscriber

ros2 run bumperbot_cpp_examples simple_publisher  
ros2 run bumperbot_cpp_examples simple_subscriber


