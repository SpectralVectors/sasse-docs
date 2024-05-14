---
title: Draw Curves
description: Use the Pen Tool to draw these objects directly into your Scene.
layout: libdoc/page

category: Assets
order: 100
---
- Chain Curve
{:toc}

## Chain Curve
![Chain Curve](/assets/Assets/Draw_Curves/Chain_Curve_Preview.png)
### Object
- **End Cap 1** - select and animate an object from your scene, e.g. ball, hook
- **End Cap 2** - object for the other end of the chain
- **Chain Link** - object to make the chain itself, inside a hidden collection
### Material
- **Chain Color**
- **Chain Wear** - surface bumps and dents

## Cloud Curve
![Cloud Curve](/assets/Assets/Draw_Curves/Cloud_Curve_Preview.png)
### Geometry
- **Voxel Amount** - how many voxels to fill the cloud volume, more is greater detail and lower performance
- **Seed** - randomize cloud displacement
- **Radius Factor** - multiplier for cloud radius
- **Radius Offset** - add or subtract from overall radius
- **Scale Offset Min** - minimum size for cloud elements
- **Density** - how many points to place on the mesh
- **Displacement Scale** - how large are the lumps on the cloud
- **Displacement Strength** - how far do they extend
- **Subdivision Level** - smooths the mesh, but computationally expensive
### Material
- **Color Top**
- **Color Bottom**
- **Gradient Height**

## Intestine Curve
![Intestine Curve](/assets/Assets/Draw_Curves/Intestine_Curve_Preview.png)
### Object
- **End Cap 1**
- **End Cap 2**
### Geometry
- Line Spacing
- **Curve Resample Size** - points in the curve, determines detail level
- **Curve Resolution** - points around the curve
- **Curve Radius** - radius for multi-strand curves
- **Subdivision Level** - smooths the mesh, but computationally expensive
- **Multi-Strand**
- **Twist** - for multi-strand
- **Strands** - number of strands for multi-strand
- **Strand Spacing** - distance between strands for multi-strand, or curve radius for single strand
### Material
- **Color** - base pink color

## Lightning Curve
![Lightning Curve](/assets/Assets/Draw_Curves/Lightning_Curve_Preview.png)
### Geometry
- **Width** - width of the main bolt mesh
- **Subdivisions** - smooths the mesh, but computationally expensive
- **Displace** - how far to shift the points of the mesh
- **Sub-Bolts** - probability of adding smaller sub-bolts
### Material
- **Bolt Color**
- **Emission Strength** - how bright the mesh will be, best shown with Bloom enabled, in Standard Color Management
### Motion
- **Speed Factor**
- **Progress**

## Road Plane Curve
![Road Plane Curve](/assets/Assets/Draw_Curves/Road_Plane_Curve_Preview.png)
### Geometry
- **Displacement Scale** - width control
- **Displacement Strength** - depth / height control
- **Smooth Subdivisions** - smooths the mesh, but computationally expensive
### Material
- **Line Spacing** - length of lines / distance between
- **Road Color** - base pavement color
- **Center Line Color**
- **Outer Line Color**
- **Puddles Color** - show if puddles are enabled
### Cracks & Puddles
- **Cracks Mix** - blends cracks into the pavement
- **Cracks Scale** - size of the cracks
- **Puddles Mix** - blends puddles into the pavement
- **Puddles Scale** - size of the puddles
### Motion
- **Motion Multiplier** - speed of the animated textures

## Rope Curve
![Rope Curve](/assets/Assets/Draw_Curves/Rope_Curve_Preview.png)
### Settings
- Cable Color
- Line Spacing
- Curve Resample Size
- Curve Resolution
- Curve Radius
- SubDiv Level
- Multi-Strand
- Twist
- Strands
- Strand Spacing
- End Cap 1
- End Cap 2

## Tears / Sweat Curve
![Tears Sweat Curve](/assets/Assets/Draw_Curves/Tears_Sweat_Curve_Preview.png)
### Settings
- Radius
- Color

## Tech Cable Curve
![Tech Cable Curve](/assets/Assets/Draw_Curves/TechCable_Curve_Preview.png)
### Settings
- Cable Color
- Line Spacing
- Curve Resample Size
- Curve Resolution
- Curve Radius
- SubDiv Level
- Multi-Strand
- Twist
- Strands
- Strand Spacing
- End Cap 1
- End Cap 2
