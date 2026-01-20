# ROS 2 Wheeled Mobile Robot with Integrated Manipulator Arm

This repository contains a **ROS 2–based wheeled mobile robot** integrated with a **simple manipulator arm**, designed and simulated using **Gazebo** and **RViz**.  
The project demonstrates core concepts of **ROS 2 architecture, robot modeling, control, TF frames, and simulation-based validation**.

This project is part of my hands-on learning and portfolio development in **Robotics and Autonomous Systems using ROS 2**.

---

## 📌 Project Overview

- Differential drive wheeled mobile robot  
- Integrated single-link manipulator arm  
- Waypoint-based navigation  
- Predefined path controllers  
- Gazebo physics simulation  
- TF frame visualization and debugging in RViz  

---

## 🛠 Tools & Technologies

- **ROS 2** (Humble / Iron compatible)  
- **Gazebo** – Robot simulation  
- **RViz** – Visualization & TF debugging  
- **URDF / XACRO** – Robot description  
- **Python** – ROS 2 node implementation  
- **Git & GitHub** – Version control  

---

## 🤖 Robot Description

- **Mobile Base**: Differential drive wheeled platform  
- **Manipulator**: Single revolute joint arm mounted on the base  
- **Control**: Velocity-based motion control via ROS 2 topics  
- **Simulation**: Full physics simulation in Gazebo  

The robot model is designed for **modularity and future expansion**, such as adding more joints, sensors, or autonomous navigation.

---

## 🧭 ROS 2 System Architecture

The project follows a standard ROS 2 communication pipeline using:

- `/cmd_vel` – Mobile robot velocity commands  
- `/joint_states` – Manipulator joint feedback  
- `/tf` and `/tf_static` – Coordinate transformations  
- Gazebo–ROS bridge for simulation integration  

---

## 🔄 ROS 2 Node & Topic Flow

The following flowchart shows the interaction between ROS 2 nodes, topics, TF frames, and the Gazebo simulation environment:

![ROS2 Flowchart](https://github.com/assirT24/ROS2-Project/blob/505a51fc136f0a238cec8d4bf2a99ced62667022/1766170181860.jpg)

---

## 🖼 Simulation Results

### 🔹 Gazebo Simulation – Mobile Robot
![Gazebo View](https://github.com/assirT24/ROS2-Project/blob/74510fe788e0d79a456e09cd2b109af1050d0aa0/1766170180832.jpg)

---

### 🔹 TF Frames Visualization in RViz
![TF Frames](https://github.com/assirT24/ROS2-Project/blob/74510fe788e0d79a456e09cd2b109af1050d0aa0/1766170180857.jpg)

---

### 🔹 Manipulator Interaction with Environment
![Manipulator Interaction](https://github.com/assirT24/ROS2-Project/blob/553aa52a8ab23792e52c8db4cdc421adc7375c38/1766170180911%20(1).jpg)

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/assirT24/ROS2-Project.git
cd ROS2-Project
```

### 2️⃣ Build the ROS 2 workspace
```bash
colcon build
source install/setup.bash
```

### 3️⃣ Launch the simulation
```bash
ros2 launch ros2_car gazebo.launch.py
```
## 📚 Learning Outcomes

- Practical understanding of **ROS 2 node-based architecture**
- Working with **TF trees and coordinate transformations**
- Robot modeling using **URDF**
- Debugging robots in **Gazebo & RViz**
- Applying **GitHub version control** in robotics projects

---

## 🔮 Future Enhancements

- Inverse kinematics for the manipulator
- Autonomous navigation using **Nav2**
- Perception integration using camera or **LiDAR**
- Multi-joint robotic arm
- Real hardware deployment

---

## 👤 Author

**Assir Thota**  
B.Tech – Electronics and Communication (Rail Engineering)  
Gati Shakti Vishwavidyalaya, Vadodara  

- GitHub: https://github.com/assirT24  
- LinkedIn: https://www.linkedin.com/in/assir-thota-10213a288/
