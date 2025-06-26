# ROS 2 Mobile Robotics Projects

This repository contains my implementation of robotics projects from the Udemy course  
**"Self Driving and ROS 2 – Learn by Doing! Odometry & Control"** by *Antonio Brandi*.

Each course section is organized as its own ROS 2 package inside the `src/` directory and includes my own notes, experiments, and code written during the course.

---

## ROS 2 Packages

| Package Name              | Description                                | Language |
|--------------------------|--------------------------------------------|----------|
| `bumperbot_py_examples`  | Basic publisher/subscriber (Section 1)     | Python   |
| `bumperbot_cpp_examples` | Basic publisher/subscriber (Section 1)     | C++      |
<!-- Future entries: -->
<!-- | `odom_controller_py`       | Odometry & Kinematics                     | Python   | -->
<!-- | `pid_controller_cpp`       | PID Speed & Steering Control              | C++      | -->

---

## How to Build & Run

### Build the workspace
```bash
cd bumperbot_ws
colcon build
source install/setup.bash
```
### Run Section 1 Examples
```bash
ros2 run bumperbot_py_examples simple_publisher
ros2 run bumperbot_py_examples simple_subscriber
```

---

## Attribution

This repository is based on the Udemy course  
**"Self Driving and ROS 2 – Learn by Doing! Odometry & Control"** by [Antonio Brandi](https://www.udemy.com/user/antonio-brandi/).

The original course materials and reference code can be found on  
[Antonio Brandi's GitHub](https://github.com/AntoBrandi), and are distributed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

All code in this repository was written by me while following along with the course and is adapted for personal learning and portfolio use.  
This repository does **not** include any proprietary course assets (videos, PDFs, quizzes, etc.), and is shared respectfully under the terms of the course and license.

## 📝 Notes

- [Section 01 – Pub/Sub Basics](notes/section_01_pubsub.md)
