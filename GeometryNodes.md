---
title: Geometry Nodes
description: List of SASSE Library Effects.
layout: libdoc/page

category: Linework
order: 300
---
- Draw Lines
{:toc}

## Draw Lines
![Draw Lines](/assets/Linework/GeometryNodes/Draw_Lines_Preview.png)
### Geometry
- **Thickness** - base line thickness
- **Width Min** - minimum thickness
- **Width Max** - maximum thickness

### Material
- **Color** - line color

## In & Outline
![In & Outline](/assets/Linework/GeometryNodes/In_Outline_Preview.png)
### Outline
- **Outline** - enable outline mesh
- **Outline Material** - outline shader
- **Outline Color** - color of outline shader
- **Outline Thickness** - thickness of outline mesh

### Inner Lines
- **Inner Lines** - enable inner line mesh
- **Inner Line Material** - inner line shader
- **Inner Line Color** - color of inner line shader
- **Inner Line Thickness** - base inner line thickness
- **Width Min** - minimum inner line thickness
- **Width Max** - maximum inner line thickness
- **Offset** - offset inner lines by mesh normals
- **Initial Subdivisions** - smooth base mesh and inner line meshes before generating lines (may require adding support loops to keep lines in place)
- **Smooth Subdivisions** - smooths the meshes after line generation

### Motion
- **Frame Jitter** - adds small motion during playback to simulate imperfections in line art

### Culling
- **Cull Backfaces** - remove unseen faces (requires Cull Camera)
- **Cull Camera** - Camera perspective used for face culling

## Simple Outline
![Simple Outline](/assets/Linework/GeometryNodes/Simple_Outline_Preview.png)
### Outline
- **Outline Material** - outline shader
- **Outline Color** - color of outline shader
- **Outline Thickness** - thickness of outline mesh
- **Subdivision Level** - smooths the meshes

### Motion
- **Frame Jitter** - adds small motion during playback to simulate imperfections in line art
