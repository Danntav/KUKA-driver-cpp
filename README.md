# KUKA Driver in C++

This repository contains the development of a lightweight and simulation-compatible driver for KUKA industrial robots, written in C++.

The goal is to create a modular, standalone driver that communicates directly with KUKA robots over TCP/UDP sockets, without relying on GPL-licensed software or proprietary middleware. The first phase of development is focused on integration with **RoboDK** as a simulation backend, and future iterations may explore compatibility with **ROS 2**.

## Objectives

- [x] Simulate robot motion using RoboDK and its C++/Python API
- [x] Create a basic driver architecture in C++
- [x] Implement TCP/UDP communication layer
- [ ] Allow command parsing and execution from external systems
- [ ] Enable joint position control and feedback
- [ ] ROS 2 integration

## Technologies

- C++
- RoboDK API
- Sockets (TCP/UDP)
- CMake (build system)
- [Future] ROS 2
- [Future] Gazebo

## Structure

```bash
kuka-driver-cpp/
├── src/            # Source code
├── include/        # Header files
├── test/           # Unit or integration tests
├── docs/           # Design documents, reports
└── CMakeLists.txt  # Build instructions
