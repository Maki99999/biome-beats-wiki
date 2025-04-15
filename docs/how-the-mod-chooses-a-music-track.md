---
sidebar_position: 4
---

# How the Mod Chooses a Music Track

The mod continuously monitors active conditions and determines which music to play by following these steps:
1. Identifies the highest priority among the met conditions.
2. Filters out any conditions that don’t match this priority.
3. Gathers all music tracks associated with the remaining conditions.
4. If the currently playing track isn’t in this list, it selects a new track randomly from the list.

Recently played tracks are tracked to avoid back-to-back repeats if possible.