[![SHILED1](https://img.shields.io/badge/SPACE-Robotics-orange.svg)](link_to_your_project) [![SHILED1](https://img.shields.io/badge/KTH-DHSG-green.svg)](link_to_your_project) [![SHILED1](https://img.shields.io/badge/ROS-Humble-blue.svg)](link_to_your_project) [![SHILED1](https://img.shields.io/badge/GAZEBO-Classic_v11-blue.svg)](link_to_your_project)

# ROS 2 Simulator Messages

This repository contains custom ROS 2 messages used in the International Space Station (ISS) simulation project for robotics research and space inspection missions.

## Messages

The ROS 2 messages defined in this repository are tailored for simulating orbital dynamics and space robotics tasks. They include:

- `ComputeRelativeInitialConditions`: Service message for computing relative initial conditions based on orbital parameters.
- `PhaseAmplitude`: Message containing phase and amplitude data for stable relative orbits.
- `Wrench`: Message representing wrench (force and torque) data in 3D space.

These messages are used to facilitate communication between different components of the simulation system, including ROS 2 nodes, Gazebo simulation plugins, and external controllers.

## Installation

Clone this repository into your ROS 2 workspace and build it using `colcon` or `ament`.

```bash
cd /path/to/your/ros2_workspace/src
git clone <repository_url>
cd ..
rosdep install --from-paths src --ignore-src -y
colcon build
source install/setup.bash



This README template provides a concise overview of the repository content, focusing on the custom ROS 2 messages used in the ISS simulation project. It includes sections for describing the purpose of the repository, the specific ROS 2 message types, installation instructions, usage guidelines, and developer contact information.

Feel free to modify the content further based on your specific repository and project requirements. This template aims to provide a clear and informative README for users and contributors to understand the purpose and usage of the ROS messages within your ROS 2 simulator project.

# Developers
Gregorio Marchesini [gremar@kth.se](mailto:gremar@kth.se)

Pedro Roque [padr@kth.se](padr@kth.se)

