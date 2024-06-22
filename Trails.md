---
title: Trails
description: List of SASSE Library Effects.
layout: libdoc/page

category: Effects
order: 200
---
- Light Trail
{:toc}

## Light Trail
![Light Trail](/assets/Effects/Trails/LightTrail_Preview.png)
### Object
- **Use Vertex Group** - spawn single trail at object origin, or instance multiple trails on vertices
- **Vertex Group** - vertex group to instance trails (if Use Vertex Group is selected)

### Geometry
- **Resolution** - number of points around trail curve mesh
- **Length** - length of the trail (shader)
- **Radius** - thickness of the trail
- **Spacing** - space between trails (if Vertex Group is selected)
- **Subdivision Level** - smooths the trail mesh
- **Offset** - location offset of trail mesh (or meshes)

### Material
- **Color 1** - inner color
- **Color 2** - outer color

## Speed Lines Trail
![Speed Lines Trail](/assets/Effects/Trails/Speed_Lines_Trail_Preview.png)
### Object
- **Use Vertex Group** - spawn single trail at object origin, or instance multiple trails on vertices
- **Vertex Group** - vertex group to instance trails (if Use Vertex Group is selected)

### Geometry
- **Resolution** - number of points around trail curve mesh
- **Length** - length of the trail (shader)
- **Radius** - thickness of the trail
- **Spacing** - space between trails (if Vertex Group is selected)
- **Subdivision Level** - smooths the trail mesh
- **Offset** - location offset of trail mesh (or meshes)

### Material
- **Line Color** - color of the speed lines
- **Line Scale** - line scale
- **Line Distortion** - secondary line scale

### Motion
- **Speed Factor** - speed of the line motion
