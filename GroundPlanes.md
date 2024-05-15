---
title: Ground Planes
description: List of SASSE Library Effects.
layout: libdoc/page

category: Assets
order: 100
---
- Cracked Rock Plane
{:toc}

## Cracked Ground Plane
![Cracked Ground Plane](/assets/Assets/Ground_Planes/Cracked_Ground_Plane_Preview.png)
### Geometry
- **Size X** - size of the plane on the X axis
- **Size Y** - size of the plane on the Y axis
- **Mesh Resolution** - number of vertices along each axis
- **Displacement Scale** - how wide is the displacement
- **Displacement Strength** - how deep / high is the displacement
- **Subdivision Level** - smooths the mesh at the cost of performance
### Material
- **Color** - base color of the plane
- **Cracks Scale** - size of the cracks on the surface

## Grass Plane
![Grass Plane](/assets/Assets/Ground_Planes/Grass_Plane_Preview.png)
### Geometry
- **Size X** - size of the plane on the X axis
- **Size Y** - size of the plane on the Y axis
- **Displacement Scale** - how wide is the displacement
- **Displacement Strength** - how deep / high is the displacement
- **Displacement Subdivisions** - how much to subdivide the mesh prior to displacement
- **Smooth Subdivisions** - smooths the mesh at the cost of performance
### Grass
- **Grass Height** - height of each grass blade
- **Grass Density** - how many blades of grass will be distributed on the plane
- **Realize Geometry** - determines texture mapping, toggle for performance
### Material
- **Grass Color** - base color of the grass
- **Grass Color Noise Scale** - how large are the variations in the color
### Motion
- **Auto-Animate** - rotates the grass blades to simulate wind
- **Speed** - how fast will the blades turn
- **Blade Rotation Range** - how far will the blades turn

## Ice Plane
![Ice Plane](/assets/Assets/Ground_Planes/Ice_Plane_Preview.png)
### Geometry
- **Size X** - size of the plane on the X axis
- **Size Y** - size of the plane on the Y axis
- **Mesh Resolution** - number of vertices along each axis
- **Displacement Scale** - how wide is the displacement
- **Displacement Strength** - how deep / high is the displacement
- **Subdivision Level** - smooths the mesh at the cost of performance
### Material
- **Color** - base color of the plane
- **Cracks Scale** - size of the cracks on the surface

## Sand Dunes Plane
![Sand Dunes Plane](/assets/Assets/Ground_Planes/Sand_Dunes_Plane_Preview.png)
### Geometry
- **Size X** - size of the plane on the X axis
- **Size Y** - size of the plane on the Y axis
- **Cell Size** - determines dune detail
- **Subdivisions** - smooths the mesh at the cost of performance
### Dune
- **Dune Height** - height of the dunes
- **Dune Scale** - width of the dunes, how many will fit on the plane
### Blown Sand
- **Blown Sand** - enable the blown sand effect
- **Start Height** - how high should the blown sand start
- **Grain Size** - max size of the blown sand
- **Density** - how many points to distribute
- **Wind Direction** - which direction to blow the sand
### Material
- **Sand Color** - base color of the sand plane

## Water Plane
![Water Plane](/assets/Assets/Ground_Planes/Water_Plane_Preview.png)
### Ripple & Float
- **Collection** - place objects in this collection to have them float on the water and cause ripples
### Waves
- **Wave Width** - space between waves
- **Wave Height** - height of the waves
- **Wave Offset** - shift the wave forward or back
### Foam
- **Start Height** - height to start generating foam
- **Density** - how many foam 'balls' to add
- **Voxel Size** - determines detail, how small is the smallest voxel
### Material
- **Water Color** - base color of the water
- **Foam / Highlight Color** - color of the foam and the highlights on the water
### Motion
- **Speed Multiplier** - how fast will the waves move
