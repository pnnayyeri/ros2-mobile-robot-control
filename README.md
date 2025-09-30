# ros2-mobile-robot-control
ROS2-based mobile robot simulation with navigation, SLAM, and obstacle avoidance


A ROS2-based mobile robot simulation with navigation, SLAM, and obstacle avoidance, built for demonstrating robotics software engineering and control expertise.

🚀 Features

Robot Simulation: Differential-drive robot in Gazebo/Isaac Sim.

Navigation Stack: Path planning and obstacle avoidance.

SLAM: Mapping and localization with LIDAR or depth camera.

ROS2 Packages: Modular nodes with launch files.

Dockerized Setup: One-line install and run for reproducibility.

📂 Repository Structure
ros2-mobile-robot-control/
│── src/                # ROS2 packages
│   ├── robot_description/   # URDF, meshes
│   ├── robot_bringup/       # Launch files
│   ├── robot_navigation/    # Nav2 config
│   ├── robot_slam/          # SLAM config
│── worlds/             # Gazebo world files
│── docker/             # Docker build files
│── scripts/            # Utility scripts
│── docs/               # Documentation and diagrams
│── README.md           # This file
