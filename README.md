<h1 align="center">Eduardo Iván Ángeles Rodríguez</h1>

<p align="center">
  Robotics Engineering Student · ROS 2 · Autonomous Systems · Embedded Robotics
</p>

<p align="center">
  I build robotic systems that connect simulation, perception, planning, control and physical hardware.
</p>

<p align="center">
  <a href="https://www.areivan.com/">Portfolio</a> ·
  <a href="https://github.com/AREIVAN">GitHub</a>
</p>

---

## About

My work is focused on **systems robotics**: integrating the software, models, sensors, controllers and hardware required to make a robot behave as one coherent system.

My current direction is centered on quadruped robotics with the **Unitree Go2**, using ROS 2 and simulation as the foundation for:

- Robot modeling and simulation with Gazebo Harmonic
- Model-based locomotion and contact-aware control
- Reinforcement learning experiments in MuJoCo
- Perception, navigation and behavior architectures
- Embedded and industrial interfaces for real-world systems

I prefer projects with explicit interfaces, reproducible environments, measurable behavior and honest documentation of what is implemented versus planned.

## Robotics workflow

```text
Perception → State Estimation → Planning → Control → Actuation
       ↘ Simulation, Visualization, Validation and Telemetry ↗
```

## Selected work

### 🐕 [Unitree Go2 — ROS 2 Jazzy + Gazebo Harmonic](https://github.com/AREIVAN/Unitree-Go2-ROS-2-Jazzy-Gazebo-Harmonic-Simulation)

A ROS 2 simulation stack for the Unitree Go2 with Gazebo Harmonic, `ros2_control`, effort interfaces, a PD standing controller and RViz2 visualization.

**Focus:** simulation infrastructure, robot descriptions, controller integration and reproducible launch workflows.

### 🦿 [ROS 2 Quadruped Locomotion Control](https://github.com/AREIVAN/ROS2-Quadruped-Locomotion-Control)

A model-based locomotion framework connecting velocity commands to joint-level control through contact scheduling, support geometry, wrench allocation, stance/swing planning and inverse kinematics.

**Current direction:** validating contact transfer and building toward repeatable forward locomotion and a robot-independent controller architecture.

### 🧠 [Unitree Go2 RL Locomotion](https://github.com/AREIVAN/Unitree-Go2-RL-Locomotion)

MuJoCo-based experiments with locomotion policies, RSL-RL/PyTorch workflows and local keyboard teleoperation.

**Focus:** comparing learned locomotion with explicit model-based control.

### 🐾 [InstinctOS](https://github.com/AREIVAN/InstinctOS)

An early-stage ROS 2 simulation scaffold for behavior-driven quadruped autonomy.

The project explores how perception, navigation, internal state and behavior priorities can produce behaviors such as `EXPLORE`, `APPROACH`, `FOLLOW`, `SEARCH` and `RECOVER`.

### 📦 [ROS 2 Autonomous Warehouse Robot](https://github.com/AREIVAN/ROS-2-Autonomous-Warehouse-Robot)

A modular architecture for simulated warehouse autonomy using robot description, Nav2, localization, mapping, obstacle avoidance and mission-level control.

**Future direction:** fleet coordination, docking, battery-aware missions, visual shelf identification and eventual hardware deployment.

## Supporting projects

- [ROS2-MACoS](https://github.com/AREIVAN/ROS2-MACoS) — a remote robotics workstation workflow for running ROS 2 and RViz2 on WSL2 from macOS.
- [ESP32 Industrial Wi-Fi Alert Actuator](https://github.com/AREIVAN/esp32-industrial-wifi-alert-actuator) — an embedded signaling prototype with an OLED status display and relay output.
- [ADACHI-BOARD](https://github.com/AREIVAN/ADACHI-BOARD) — a custom ESP32-S3 control board for Mini Sumo robotics.

## Current development

I am working toward a connected robotics portfolio that moves through these layers:

1. **Simulation:** reliable robot models, controllers and test environments.
2. **Locomotion:** contact-aware control, gait generation and learned policies.
3. **Autonomy:** perception, localization, navigation and behavior orchestration.
4. **Hardware:** embedded interfaces and physical robotic platforms.
5. **Validation:** repeatable experiments, diagnostics and sim-to-real constraints.

## Technology

`ROS 2` · `Gazebo Harmonic` · `Nav2` · `RViz2` · `ros2_control` · `MuJoCo` · `Python` · `C++` · `PyTorch` · `OpenCV` · `ESP32` · `KiCad` · `Linux`

## Engineering principles

- **Simulation first, hardware aware**
- **Modular interfaces over isolated demos**
- **Validation before claiming capability**
- **Documentation as part of the engineering work**
- **Open experimentation with clear technical limits**

I am interested in collaborating on robotics, autonomous systems, embedded control and industrial automation projects.

<p align="center">
  Building robotic systems from simulation to hardware.
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AREIVAN/AREIVAN/main/dist/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AREIVAN/AREIVAN/main/dist/github-snake.svg">
    <img alt="GitHub Contribution Snake Animation" src="https://raw.githubusercontent.com/AREIVAN/AREIVAN/main/dist/github-snake.svg">
  </picture>
</p>

