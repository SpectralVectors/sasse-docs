---
title: Rain
description: List of SASSE Library Effects.
layout: libdoc/page

category: Effects
order: 200
---
- Rain Planes
{:toc}

## Rain Planes
![Rain Plane](/assets/Effects/Rain/Rain_Plane_Preview.png)
### Geometry
- **Count** - number of planes
- **Spacing** - distance between planes
- **Scale by Distance** - scale up distant planes to cover in-camera area

### Material
- **Color** - rain color

### Motion
- **Speed Multiplier** - speed of rainfall

## Rain System
![Rain System](/assets/Effects/Rain/Rain_Splashes_Preview.png)
### Collision
- **Collision Collection** - place objects in this collection to block rain and cause 'splashes'
- **Kill Plane** - a 'ground' object to kill raindrops
- **Kill Height Offset** - a world height at which to kill any stray rain drops

### Geometry
- **Drop Length** - length of rain drops
- **Drop Radius** - width of rain drops
- **Density** - how many drops will be spawned
- **Drop Subdivisions** - how smooth are the drops
- **Splash Subdivisions** - how smooth are the splashes

### Splashes
- **Scale by Age** - grow and shrink splashes over time
- **Lifetime** - number of frames a splash will last
- **Height** - max height of splashes
- **Width** - max width of splashes
- **Offset** - offset location of splashes spawning

### Material
- **Rain Color** - color of rain and splashes

### Motion
- **Speed** - how fast is the rainfall
