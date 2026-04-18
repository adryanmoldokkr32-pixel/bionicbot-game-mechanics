---
name: animation-state-machine
description: Manage transitions between different animation states (Idle, Run, Attack).
---

# Animation State Machine

This skill focuses on the logic that decides which animation should play at any given moment.

## Instructions

1. Define animation states and their associated clips.
2. Create transition parameters (Speed, IsGrounded, IsAttacking).
3. Set up blending between states for smooth movement (e.g., Walk to Run).
4. Use 'layers' to play animations on specific body parts (e.g., Reloading while Running).
5. Implement logic-driven root motion for realistic foot placement.

## Examples

- "Set up a character animation controller with 5 distinct states."
- "Debug a transition issue where the character skips the 'Jump' animation."