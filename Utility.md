---
title: Utility
description: List of SASSE Library Materials and Shaders.
layout: libdoc/page
category: Node Groups
order: 500
---
A series of Node Groups to facilitate stepped and oscillating motion in Shaders and Geometry Nodes.
## LFO
Outputs an oscillating signal, good for repetitive movements, e.g.: hovering, pendulum, blinking lights etc
- **Sine / Square** - mix between smooth and stepped motion
- **Frequency** - speed of the movement
- **Depth** - distance of the movement
- **Offset** - shift the starting point of the movement

## TimeStep Attributes GN
Outputs stepped motion in the Geometry Nodes Editor, and creates named attributes in the scene.
- **Ones** - updates every frame
- **Twos** - updates every second frame
- **Threes** - updates every third frame
- **Fours** - updates every fourth frame

## TimeStep GN
Outputs stepped motion in the Geometry Nodes Editor.
- **Ones** - updates every frame
- **Twos** - updates every second frame
- **Threes** - updates every third frame
- **Fours** - updates every fourth frame

## TimeStep Menu GN
Outputs selectable stepped motion in the Geometry Nodes Editor.
- **Output** - select between Ones, Twos, Threes and Fours

## TimeStep SN
Outputs stepped motion in the Shader Nodes Editor.
- **Ones** - updates every frame
- **Twos** - updates every second frame
- **Threes** - updates every third frame
- **Fours** - updates every fourth frame
