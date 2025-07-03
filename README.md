# Minibot - Custom Robot Configuration

This repository contains a customized version of a differential drive robot project built with ROS 2 Jazzy Jalisco. The modifications made to this repository are specifically tailored to the requiremnts for the Bachelor thesis: Autonomous Robot for Plant Management and Energy Efficiency on Photovoltaic Green Rooftops.

## Custom Modifications

The changes made to this repository from the original project include:

### Robot Description Updates
- **Description Folder**: Modified the robot description files in the `description/` folder to match the specifications of the physical robot hardware
- Updated URDF/Xacro files to accurately represent the custom robot's physical properties, sensors, and actuators

### Launch File Modifications
- **robot.launch.py**: Customized the main launch file to integrate with specific hardware components
- Added `node_rplidar_drive` to support RPLidar sensor integration for the physical robot
- Configured launch parameters to match the custom hardware setup and sensor configurations

### Hardware Integration
- Configured the launch system to work seamlessly with the physical robot's hardware components
- Integrated RPLidar sensor driver for real-world SLAM and navigation capabilities
- Adjusted controller configurations to match the robot's drive system

## Features

This customized robot setup includes:
- Differential drive control system
- RPLidar integration for mapping and navigation
- ROS 2 control framework
- Custom robot description matching physical hardware
- Teleoperation capabilities
- SLAM and Navigation2 integration

## Getting Started

1. Ensure you have ROS 2 Jazzy Jalisco installed on Ubuntu 24.04
2. Clone this repository to your workspace
3. Build the package using `colcon build`
4. Source the workspace and launch the robot using the provided launch files

## Hardware Requirements

- Differential drive robot platform
- RPLidar sensor
- Compatible microcontroller/single-board computer
- Appropriate motor drivers and sensors as defined in the robot description

## Original Documentation

Check out `README-orig.md` for the original documentation and functionality.

## License

This project maintains the MIT License from the original project.
