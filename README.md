# ros2-mobile-robot-control  
A ROS2-based mobile robot simulation with navigation, SLAM, and obstacle avoidance, built for demonstrating robotics software engineering and control expertise.  

---

## 🚀 Features  
- **Robot Simulation**: Differential-drive robot in Gazebo/Isaac Sim.  
- **Navigation Stack**: Path planning and obstacle avoidance.  
- **SLAM**: Mapping and localization with LIDAR or depth camera.  
- **ROS2 Packages**: Modular nodes with launch files.  
- **Dockerized Setup**: One-line install and run for reproducibility.  

---

## 📂 Repository Structure  
ros2-mobile-robot-control\
│── src/ # ROS2 packages\
│ ├── robot_description/ # URDF, meshes\
│ ├── robot_bringup/ # Launch files\
│ ├── robot_navigation/ # Nav2 config\
│ ├── robot_slam/ # SLAM config\
│── worlds/ # Gazebo world files\
│── docker/ # Docker build files\
│── scripts/ # Utility scripts\
│── docs/ # Documentation and diagrams\
│── README.md # This file\

---

## ⚙️ Installation  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/ros2-mobile-robot-control.git
cd ros2-mobile-robot-control
```

### 2. Build with colcon

```bash
colcon build
source install/setup.bash
```

### 3. Run the simulation
```bash
ros2 launch robot_bringup simulation.launch.py
```

## 🕹️ Usage

### Run SLAM
```bash
ros2 launch robot_slam slam.launch.py
```

### Run Navigation
```bash
ros2 launch robot_navigation nav.launch.py
```

### Teleop (keyboard control)
```bash
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```

## 📊 Demo
Soon...


## 🛠️ Tech Stack
*ROS2 Humble
*Gazebo / Isaac Sim
*Nav2 (Navigation Stack)
*SLAM Toolbox
*Docker

## 📈 Roadmap
[ ] Add camera-based navigation
[ ] Multi-robot simulation
[ ] Deploy on physical robot

## 📜 License
MIT License. See [LICENSE](https://opensource.org/license/mit).

## 👤 Author
Pooyan Nayyeri
[LinkedIn](https://www.linkedin.com/in/pnnayyeri/)
