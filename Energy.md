---
title: Energy
description: List of SASSE Library Effects.
layout: libdoc/page

category: Effects
order: 200
---
- Energy
{:toc}

## Energy Beam Curve
![Energy Beam Curve](/assets/Effects/Energy/Energy_Beam_Curve_Preview.png)
### Geometry
- **Resolution** - number of points around the curve mesh
- **Radius** - thickness of the curve mesh
- **Taper** - shrinks one end to create a conic shape

### Material
- **Color 1** - inner color
- **Color 2** - outer color
- **Emission Strength** - intensity of brightness
- **Energy Noise** - scale of the noise blending the 2 colors
- **Falloff Noise** - scale of the noise blending the transparency
- **IOR** - additional color blend control, how much will the outer color 'wrap-around'

### Motion
- **Progress** - animate the progress of the effect

## Energy Ring
![Energy Ring](/assets/Effects/Energy/Energy_Ring_Preview.png)
### Geometry
- **Vertex Group** - the Vertex Group the effect will affect
- **Subdivision Level** - how fine / sharp are the points

### Material
- **Color 1** - wide band color
- **Color 2** - thin band color

### Motion
- **Speed Multiplier** - how fast the mesh and texture move
- **Progress** - animate the scale

## Energy Sphere
![Energy Sphere](/assets/Effects/Energy/Energy_Sphere_Preview.png)
### Material
- **Color 1** - inner color
- **Color 2** - outer color

### Motion
- **Speed Multiplier** - how fast will the texture move
- **Grow** - animate scale and texture
