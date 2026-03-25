# SOP & MVP
> In this document, I will show you the the philosophy of Standard Operating Procedure (SOP) and Minimum Viable Product (MVP), the two most common concepts in engineering, for enhancing productivity and efficiency.

## SOP
The standard operation procedure means **a set of step-by-step instructions compiled by an organization to help workers carry out routine operations that aim to achieve efficiency, quality and uniformity of performance while reducing miscommunication and failure.**[^1]

### Basic structure
Usually, a SOP is just a TODO list with tick boxes. When you reach one milestone, the box is filled with a hook.
However, an efficiency SOP is not so easy to compose.

From my perspective, an effective SOP contains **five** essential elements:
- Tailored execution plans for different circumstances. No matter the status of the team, the work can be pushed after all.
- Rigid acceptance criterion. Once the criterion is achieved, the task should be archived and the team only maintain it rather than endless polishing.
- Clear giving up boundary. The difficulty of task sometimes exceed everyone's expectations. So giving up or a strategic withdraw is required. When the reaching giving up boundary, the team should stop pushing and turn to other valuable tasks.
- Balanced work-rest relationship. 2 or 3 rest days every week. Humans are not machines that never get tired. Acknowledge the limit of human, with respecting the value of labour.
- Logging time. Maybe only 5 minutes one day, the team should reflect on itself, adjust its plan.

### Composing a Template of SOP
Usually, the format of SOP is static while the contents is volatile.
So a template sometimes works well.

In your template, you should define:
1. The RULE. For example, `GIVE UP is not failure, but strategic transition`, or `We split tasks into 3 levels according to the complexity`. These rules are hardly changed.
2. Execution unit. For example, you should define the content of one meta-task, containing the goal, criterion, giving up condition and priority.
```md
- [ ] Task Name&Accept criterion
    - Procedure 1
    - Procedure 2
    - ...
    - Abort Signal -> Do what when abort.
```

3. **Deadline**. A deadline is essential. Though a design a rigid deadline is impossible at the beginning of a project, a rough time limit still matters. The time will push the project moving forward, reminding every one that don't stay in local optimum for too long.

## MVP
> A minimum viable product (MVP) is a version of a product with **just enough features** to be usable by early customers who can then provide feedback for future product development.[^2]

The concept straightforward and easy to understand. However, not very easy to achieve. In our project, some parts such as the engine are difficult to iterate easily. A further discussion around the MVP should be held. 

### Waterfall Development + Rapid Development
Considering the complexity of our project, the best strategy might be the combination of iteration of MVP (rapid dev) and long term optimization and argumentation for complex modules (waterfall dev).

## SOP -> MVP
The two concept is tightly coupled for development.
The goal of SOP is MVP, the process of checking the criterion in SOP is a kind of MVP acceptance.

The last but not least, **they are tools but not canonical form for project**, the key of engineering is human, and the form is born for liberation of labour.

## My eg
Here is a project plan, though I don't obey the rules rigidly, it is still a nice reference.
- SOP
```md
## 1. Task Execution Rules (Global)
- Each task has **one observable abort signal**
- Abort ≠ failure → it is a controlled transition
- No task may exceed its time cap
End-of-day rule:
> Last 5 minutes are for logging only. No new tasks allowed.

---
### 2. State A Tasks (High Occupation)
- [x] A1. Read and think:... Which is better for my task ?
	- [x] 1. Get the logic of ...,
	- [x] 2. Understand how to use ...
	- [x] 3. REBUILD pipeline.
	- [x] ...
- [ ] A2. Try to combine them into diffusion pipeline
```
- MVP

Every thing starts from baseline.
```md
- [x] Baseline **Deadline xxxx 10:00AM**
- [x] Method **Deadline ...**
- [ ] Controlled Comparison **Deadline yyyy**
- [ ] Plots: **Deadline Feb yxyxx**
- [ ] Ablation Experiment **Deadline xxyy**
- [ ] Finish: First Edition:**Deadline xxxxx**
2. Baseline **Deadline xxxx 10:00AM**
```
Actually I didn't followed all rules, however, I finished the project finally.
The key of SOP and MVP is not cold execution, but follow the objective law of the workflow of human. 

Quite abstract right? Practice it.

[^1]:[wikipedia](https://en.wikipedia.org/wiki/Standard_operating_procedure)
[^2]:[wikipedia](https://en.wikipedia.org/wiki/Minimum_viable_product)