# 4-DOF Robot for Autonomous Manipulation (PyBullet Simulation)
4-DOF robotic manipulator simulated in PyBullet for autonomous manipulation and motion validation.


## Overview
This project focuses on the design and simulation of a robotic manipulation system using a physics-based environment in PyBullet. It explores how perception and learning-based approaches can be used to guide robot actions for tasks such as object manipulation.

## Features
- Physics-based simulation using PyBullet  
- Robot motion control using inverse kinematics  
- Vision-based perception input from simulation environment  
- Learning-based action generation using a pretrained model  
- End-to-end pipeline from perception to execution  

## System Workflow
Perception (Camera Input) → AI Model → Action Generation → Robot Control → Task Execution  

## Tools & Technologies
- Python  
- PyBullet  
- Transformers (Vision-Language-Action model)  
- NumPy  

## Project Structure
- `main.py` → Complete pipeline integrating perception, decision-making, and robot control  
- `simulation` → PyBullet environment setup (robot, objects, physics)  
- `control` → Inverse kinematics and joint-level motion control  
- `perception` → Image capture and processing from simulation  

## Current Status
- Simulation environment implemented and tested  
- Robot motion and control validated  
- AI-based action generation integrated  
- End-to-end manipulation pipeline demonstrated in simulation  

## Key Learnings
- Understanding of robotic kinematics and control  
- Experience with physics-based simulation environments  
- Exposure to perception-driven and learning-based robotics  
- Integration of AI models with robotic systems  

## Future Scope
- Integration of real-time perception and feedback  
- Improvement of manipulation accuracy and robustness  
- Exploration of reinforcement learning approaches  
- Transition from simulation to real-world robotic system  

## Note
This project is currently simulation-based. Hardware implementation and advanced perception modules are part of ongoing work.-based. Hardware integration and perception modules are part of ongoing work.
