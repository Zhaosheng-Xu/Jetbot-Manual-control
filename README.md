# JetBot Manual Control Project
# Project Overview
This repository documents the implementation of manual control functionality for the JetBot robot using a gamepad controller. The project is part of an extra credit assignment focused on JetBot-based track racing and robotics application development. While the autonomous driving task is still under development, this submission demonstrates a fully operational manual driving system.
# Objective
The primary goal of this task is to manually navigate the JetBot through a predefined racetrack using intuitive human input via a gamepad. This forms the foundation for later autonomous control modules.

# Completed Task

### Task 1: Manual Controlled Racing

- Developed and tested a gamepad-controlled JetBot using the "teleoperation example" from JetBot's official tutorials.
- Verified JetBot responds accurately to directional commands: forward, backward, left, and right.
- Successfully completed three full laps around the racetrack in manual mode.
# Control Method

- Controller: DualShock (can support others via 'widgets.Controller(index=0)')
- Interface: Gamepad values linked via 'ipywidgets.jsdlink()' to control robot motion
- Platform: NVIDIA Jetson Nano running JetBot with JupyterLab interface
- ![image](https://github.com/user-attachments/assets/4f1d77e9-b42b-416a-85e5-0e0ef225e695)


# Technologies Used

- Python 3.7+
- JetBot API (`jetbot`, `traitlets`, `widgets`)
- Jupyter Notebook
- ipywidgets
- Linux (Jetson Nano Ubuntu)

# Demonstration Video
https://youtu.be/kVHuE_rD8ak?si=bsCqIgKOo7SyUGlp

# License

This project is licensed under the [MIT License](LICENSE).

# Acknowledgements

- NVIDIA JetBot Project: https://github.com/NVIDIA-AI-IOT/jetbot  
- SIUE JetBot Track Racing Assignment – Extra Credit Group Project




