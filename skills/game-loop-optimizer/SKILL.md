---
name: game-loop-optimizer
description: Optimize the core engine loop for high frame rates and stability.
---

# Game Loop Optimizer

This skill focuses on the performance of the 'Heartbeat' of a game, ensuring smooth execution regardless of hardware.

## Instructions

1. Identify bottlenecks in the Update vs. Draw cycles.
2. Implement fixed-timestamp updates for physics consistency.
3. Optimize draw calls and state changes on the GPU.
4. Use object pooling to reduce garbage collection spikes.
5. Monitor memory usage and prevent leaks in long sessions.

## Examples

- "Improve the FPS of my Godot game by optimizing the main loop."
- "Implement object pooling for a bullet-hell style game."