> This document serves as a conceptual guide rather than a rigid execution standard. Please exercise critical judgment when applying these principles.
# Knowledge Tree (KTree)
Here we introduce the definition of Knowledge Tree (KTree).
KTree is a framework for guiding iterative optimization and progress planning, containing nodes serve as **acceptable milestones** while edges are **requirements toward the milestone**.
The tree contains branches indicating independent technique paths, and the final goal is placed at the root node.
## Build a Tree
KTree aligns with standard tree structure. One node here serves as an acceptable stage (goal) to reach, whereas an edge represents the path to the goal, including prerequisite knowledge or software environments. Here is one eg of branch:
```text
	   ...
	    |
		| Edge:  
		| Learn to read MPU6050
		| Euler angle representation
		| Basic integral
		|
------------------------------
| Node : Linear Kalman Filter|
| Criteria : get 3 axis pose |
------------------------------
		|
		| Edge: 
		| Learn Quarternion
		| Jacobian linear approximation ....
		|
		... then next node...
```

> **Node and edge**
>Edge is path and requirements, while node is goal with acceptable criterion. Once the criterion is reached, we pass the node without mercy (don't pursue best here, but design criterion carefully at beginning).
>Eg: Though Kalman Filter is a kind of method, however the goal, getting pose, is acceptable and measurable. 
>We can build the system with reaching nodes, but not edges. 

One branch of the tree can be composed just like that, while each branch serves as **an independent technique path**, we should decouple all techs to our best, for minimizing the influence between different subsystems.

Finally, all branches will merge into our final goal. From `Kalman Filter` to `Attitude Estimation` then `Control Rocket`. Here is the node on one branch just like DFS, the full tree should contains deeper nodes and more branches.

---
## Usage of Tree
The philosophy behind a Minimum Viable Product (MVP) is not full-stack mastering but loops with phased iterations.
This procedure is align with the progress on the tree. We start from the minimal leaf edge (or node that contains nothing), and light nodes progressively. We can build our first version with several sparse nodes, while our final project will contains all nodes. However, our product will be actionable after the first version though that version could appear poor.
> **What is MVP?**
>When we developing sth, usually we don't build the final version once, but iterate our product iteratively. The first runnable version, containing the most stable techniques and basic systems is called MVP. Then all enhancement and changes are based on that version.

## Pruning
Aware of the progress. Our main philosophy is MVP, the bypath branches should be pruned without mercy, or ranked lower than main trunk. Designing the progress carefully is needed after building the tree, too.