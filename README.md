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

![ROS2 Flowchart](images/ros2_flowchart.png)

---

## 🖼 Simulation Results

### 🔹 Gazebo Simulation – Mobile Robot
![Gazebo View](images/gazebo_view_1.png)

---

### 🔹 TF Frames Visualization in RViz
![TF Frames](images/tf_frames.png)

---

### 🔹 Manipulator Interaction with Environment
![Manipulator Interaction](images/gazebo_view_2.png)

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/assirT24/ROS2-Project.git
cd ROS2-Project

