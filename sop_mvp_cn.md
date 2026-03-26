> Translated by Gemini

# 标准作业程序 (SOP) 与 最小可行性产品 (MVP)
在本文档中，我将向大家介绍工程领域最常见的两个概念：标准作业程序 (SOP) 和 最小可行性产品 (MVP)。其核心目的在于提升团队的生产力与执行效率。
## 标准作业程序 (SOP)
标准作业程序（SOP）是指：组织为了协助工作人员执行常规业务而编制的一套详细的分步指南。其目标是在减少沟通误解和失败率的同时，实现效率、质量和表现的统一。[^1]

### 基础结构
通常，SOP 就像一个带有复选框的 TODO 列表。当你达到一个里程碑时，框内就会被打上勾（Hook）。
然而，编写一份高效的 SOP 并不简单。

在我看来，一份优秀的 SOP 包含 五个 核心要素：
- 针对不同情况的定制化执行方案：无论团队当前处于什么状态，工作最终都能被推进。
- 严格的验收标准 (Acceptance Criterion)：一旦达到标准，任务就应立即归档，团队转入维护模式，而非无休止地打磨。
- 明确的放弃边界 (Giving up boundary)：任务的难度有时会超出所有人的预期。因此，有策略的撤退或放弃是必要的。当触及放弃边界时，团队应停止推进行动，转向其他更有价值的任务。
- 平衡劳逸关系：每周安排 2 到 3 天的休息时间。人类不是永不疲倦的机器。承认人类的极限，尊重劳动的价值。
- 记录时间 (Logging time)：哪怕每天只花 5 分钟，团队也应当进行自我反思并调整计划。

### 编写 SOP 模板
通常，SOP 的格式是固定的，而内容是动态的。因此，使用模板效果更好。

在你的模板中，你应该定义：

1. 规则 (The RULE)：例如，“放弃不是失败，而是战略转型”，或者“我们根据复杂度将任务分为 3 个等级”。这些规则一旦制定，极少更改。
2. 执行单元：例如，你应该定义一个“元任务”的内容，包括：目标、验收标准、放弃条件和优先级。

```Markdown
- [ ] 任务名称 & 验收标准
    - 执行步骤 1
    - 执行步骤 2
    - ...
    - 中止信号 (Abort Signal) -> 触发中止时该做什么
```
3. 截止日期 (Deadline)：截止日期至关重要。虽然在项目初期很难设计一个死板的限期，但一个粗略的时间限制仍然意义重大。时间会推动项目前进，提醒每一个人不要在“局部最优解”中停留太久。

## 最小可行性产品 (MVP)
最小可行性产品（MVP）是产品的一个版本，它拥有恰好足够的功能，可以交付给早期客户使用，并为未来的产品开发提供反馈。[^2]

这个概念直观易懂，但实现起来并不容易。在我们的项目中，某些部分（如发动机）很难进行快速迭代。因此，围绕 MVP 的进一步讨论非常必要。

### 瀑布式开发 + 快速开发
考虑到我们项目的复杂性，最佳策略可能是：针对复杂模块进行长期优化和论证（瀑布流开发），与 MVP 的快速迭代（快速开发）相结合。

## 从 SOP 到 MVP
这两个概念在开发过程中是紧密耦合的。
SOP 的目标是交付 MVP，而 SOP 中的验收标准检查本质上就是一种 MVP 的验收过程。

最后但也同样重要的一点是：它们只是工具，而不是项目的教条格式。 工程的关键在于“人”，所有的形式都是为了解放劳动力而诞生的。

## 示例 (My eg)
以下是一个项目计划，虽然我没有死板地遵守所有规则，但它仍是一个很好的参考。

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

事实上，我并没有完全遵守所有规则，但我最终完成了项目。
SOP 和 MVP 的关键不在于冷酷地执行，而在于遵循人类工作流的客观规律。

听起来很抽象？去实践它。


[^1]:[wikipedia](https://en.wikipedia.org/wiki/Standard_operating_procedure)
[^2]:[wikipedia](https://en.wikipedia.org/wiki/Minimum_viable_product)