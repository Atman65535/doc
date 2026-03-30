# Milestone

The concept of MVP is quite difficult for beginner, however, milestone works with less complexity.

## Milestone
Actually, we usually call it "task".
However, I have to declare what should a task contain.
Milestone is a kind of task contains a normal task with acceptance criterion.

## Example
```markdown
# Task

## Content
- Attention Hijack
- Replace all self-attention in the UNet
- Save attention maps on CPU

## Criterion
- python file with class : AttentionStorage, AttentionHook, CustomProcessor
- Replace the module in vanilla diffusion and run one generate loop, then get sound images
  
```
Here is an example for minimum milestone. Each task that distributed to members should contain similar architecture with criterion.
If the result of task meets the criterion, then we can determine that task success, otherwise, we should modify the task or send the task to another propriate member for push forward.



