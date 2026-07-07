# automatic-tool-changer-abb-irb1200
ATC For Engine Block Assembly Using ABB IRB-1200
# Automatic Tool Changer for Engine Block Assembly

Final year engineering project — an automatic tool changer system for an industrial robotic 
assembly line, built on the ABB IRB 1200 6-axis robot.

## Overview
This project automates end-effector switching for engine block assembly, allowing a single 
robot arm to handle both engine blocks and engine heads without manual tool changes or 
downtime.

## Features
- **Dual end-effector system**
  - Electromagnetic gripper for handling engine blocks
  - Two-jaw pneumatic gripper for handling engine heads
- **Wireless power transmission** to end effectors using Pogo Pin connectors — removes cable 
  interference during robot motion
- Integrated with ABB IRB 1200 6-axis industrial robot for precise, repeatable assembly motion

## Tech Stack
- ABB IRB 1200 (6-axis industrial robot)
- ABB RobotStudio / RAPID programming
- ESP to Presise control For gripper
- Wireless power transfer module
- Mechanical gripper system

## Motivation
Traditional tool-changing setups rely on physical cabling to end effectors, which introduces 
wear, snagging risk, and motion restrictions. This project solves that by transmitting power 
wirelessly, enabling cleaner, faster, and more reliable tool changes during high-speed assembly.

## Author
Pranesh E — B.E. Robotics and Automation, Sri Ramakrishna Engineering College
