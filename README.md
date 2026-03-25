# General Engineering Administration

## Hero Section

## Abstract
This repository is a documentation for those want to enhance team efficiency or carrying forward a personal project productively.

We propose four step circular project steps for push forward a project, with a set of auxiliary mental models for achieving the goal of efficient and deterministic.

## Features

<img src="./assets/architecture.png" width=300 alt="Whole architecture" align="center">

### [Four step workflow](./workflow/superior_architecture_work_flow_en.md):
- Target analysis & MVP design
- MVP decomposition with task assignment
- Forward with supervision
- Check and enter next MVP  

### Auxiliary Models for Administration:
- Execution

    The execution layer is the most part close to every developer.
    The models listed below could be applied to all projects and bring significant improvements toward the progress.

    - [Standard Operation Procedure](./mind_models/execution/sop.md)  
    The SOP enables the team (or yourself) executing the task under any harsh circumstances.
    Its core design philosophy is that making decision first, then executing strictly.
    - [Minimum Viable Product](./mind_models/execution/mvp.md)  
    MVP, the core concept of quick development.
    When the whole system is huge and unclear, we have to build small but viable products with iteratively optimization, then finally reach the ultimate goal.
    - [Milestone Tree](./mind_models/execution/milestone_tree.md)  
    One whole task should be decoupled into small pieces with an acceptance criterion.
    So that the executor can infer when to stop and how to work clearly.
    Reaching milestones will bring a sense of control to you.
    - [RACI Matrix]()
    Here we introduce RACI Matrix[^2] for better task assignment.
    Maybe this part should be placed in *responsibility* part, but I still sort it as an execution method for its highly practical property.

- Information
    
    The information layer not only provide high efficiency communication patterns, but also  contains templates for daily routes such as meeting and task decomposition.
    
    - [Daily Meeting](./mind_models/information/daily_meeting.md)  
    Usually group meeting could be poor informed and tedious. This document will help you establishing efficient meeting with problem-orientated philosophy. A simple but useful is offered. 
    - [Interface Design](./mind_models/information/interface_design.md)  
    *An interface if a shared boundary across which two or more separate components of a computer system exchange information*[^1], so as humans.
    A communication standard should be established between subsystems to ensure an efficient communication and higher compatibility.
    Here we offer instruction toward interface designing and a template for quick application.
    - [Conflict Solving](./mind_models/information/conflict_solving.md)  
    This document is more oriented to team for decision.
    While conflicts appear, they should be reported to superiors.

- Responsibility
    This part is only for team or members in a collaborated project.
    The core experience is that: **define a clear responsibility boundary between members initially.**
    - [Responsibility Boundary](./mind_models/responsibility/responsibility_boundary.md)
    This document show the importance of responsible boundary for avoiding the inequality in team. Everyone should work for themselves first, then the team. Everyone should be valued rather than regarded as a bolt.

## Examples 
Here we provide 3 examples for reference.
- [Mobile SLAM Development Platform](./examples/mobile_slam_dev_platform.md)  
This is my personal project that building a hardware platform for developing VIO algorithms. 
Building...

- [Representation Learning Project](./examples/representation_learning_project.md)   
This is my personal project too. This project is a finished project, serving as the prototype of the administration methods above. 
The experience will be composed according to the concepts above for reference.

- [Student Team Project](./examples/student_team_project.md)  
This is a project that all members are undergraduate. This is the first application of those concepts toward a team work.

## Conclusion
In this repository, we offer a standard workflow with mind models and templated for effective project carrying forward. Three representative examples are provided for better understanding.

[^1]: [Interface from wiki](https://en.wikipedia.org/wiki/Interface_(computing))
[^2]: [Responsibility assignment matrix](https://en.wikipedia.org/wiki/Responsibility_assignment_matrix)