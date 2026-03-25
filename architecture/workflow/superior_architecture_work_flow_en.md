# Superior Architecture  & Work Flow
This document provides a overall view toward a project that extremely uncertain.
A project is divided into 4 phases. 
They are: Main Object Designation, Task Allocation, Execution, Check and Back.

The whole document will composed with an example that building a SLAM mobile develop platform.

## Main Object Designation
- [MVP](../execution/sop_mvp_en.md#mvp)
### Definition
Decompose the main object of your project into small, executable MVPs for controllable execution.

- Input: Task itself, the ultimate goal you desire.
- Output: Stages of system evolution. Composed of multiple phases of MVP.

### *EG:*
- Input: The ultimate goal of a mobile SLAM platform is :
    1. Monocular camera vision odometry.
    2. IMU + GNSS odometry.
    3. Validate optimization algorithms.
    4. Flexible enough to add LiDAR or deploy algorithms.
- Output: Stages of MVP:
    1. Basic calculation platform: RPi 5 + ubuntu server + docker with ros2 + camera with IMU+GNSS, run one monocular slam demo is OK.
    2. Add data collection system: control the motion of platform manually, independent power supply.
    3. Deploy KFs on it, learn filters.
    4. Understand the previous SLAM demo, plug in custom filter. 

> Cautious:  
> The outputs are MVPs, that contains target and acceptable criterion. While the criterion is reached, the MVP is finished.

## Task Allocation
- [RACI Matrix]()
- [Milestone Tree]()
- [Cooperation Interface]()
- [Audit Template]()
### Definition 
While you define all MVPs of your project, you can choose the one and allocate tasks to your team. The core of task is **RESPONSIBILITY** and **INTERFACE**.

- Input: one MVP
- Output: 
    1. Design interface standard.
    2. Executable task units contains goal and acceptable criterion.
    3. Binding tasks with members.

### *EG:*

## Execution
- [Group Meeting]()
- [Cascade Review]()
- [Failure Processing]()
- [Conflict Drift Up]()
### Definition
Each member should push their tasks according to their responsible border.
A communication mechanism such as group meeting should be established and held regularly.
Conflicts and failures should follow standards defined in related documents.

- Input: Task from last part, with responsibility and border.
- Output: Execution result. Actually the core of this step is the process of collaborating with efficient communication.

## Check and Back

### Definition
In this stage, the finished MVP should be evaluated with a clear criterion. 
We will start next MVP if this one can be accepted.
Or we will reflect on our process, then back to [task allocation](#task-allocation) for optimization.


## Final
In this documentation, 4 procedures are defined for a project that highly uncertain and requiring discovery and iteratively optimization.
First one step is stable for most time, while the rest 3 will be executed periodically.