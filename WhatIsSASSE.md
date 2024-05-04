---
title: What Is The SASSE Library?
description: Introduction to SASSE
layout: libdoc/page

category: Introduction
order: 0
---
- What Is The SASSE Library?
{:toc}
# Introduction
## What Is The SASSE Library?
The SASSE Library is a series of shaders, assets, effects and utilities designed to give you fast, high-quality stylized renders.

SASSE stands for Stylized Assets, Spectral Shaders and Effects.

It is an evolution of an [earlier addon](https://github.com/SpectralVectors/GhibliGenerator), designed to take advantage of Blender's Asset Browser and Geometry Nodes to give you easily accessible, procedural and customizable stylized assets and effects.

## Why Make It?
There are already many excellent toon shading setups for Blender, though for some you must adopt unique workflows to achieve the best results (e.g. UV or Normal editing, channel based lighting).

I wanted to be able to treat a stylized scene the same way I would a 'standard' 3D scene:
- apply materials (texture or shader based) to my model to determine the base color
- add regular lights to my scene that could influence the color of my model
- use diffuse, specular, emissive or glossy shading

While retaining the stylized elements that I love:
- banded, cel-shaded lighting
- outer and inner lines
- traditional art techniques and textures
- 2D animation techniques like smears, squash and stretch

And using the latest Blender tool, Geometry Nodes:
- Draw objects into your scene, like chains, beams, ropes, cables or lightning!
- Quickly access all object and shader options from a single modifier!
- Procedural textures, geometry, and animations!

This led to the development of SASSE.

## Features
### Shaders
- Banded Lighting with threshold (turn up or down the number of bands)
- Colored Light! Light your stylized scene with color!
- Light Path or Vector Math based shading
- Diffuse, Specular, Glossy, Transparent Base Shaders
- Specialized Glass, Tears, Holofoil and Halftone Shaders
- Customize surface, light band and rim light normals with animatable textures

### Linework
- Geometry Node based lines
- Quick drag and drop, single modifier outline
- Inner Lines via Edge Marks - similar to Line Art Modifier workflow
- Inner Line Profile - taper ends for a hand-drawn look
- Frame Jitter to simulate hand-drawn imperfections
- Camera Culling to boost performance
- Color and Thickness control in one location
- Drag and Drop Action Lines modifier
- Draw Lines directly onto your objects or into your scene with the Pen Tool
- Also includes a LineArt modifier setup with predefined color palette and noise modifier

### Assets
- Draw assets into your scene with the Pen Tool
- Common toon objects and surfaces
- Procedural and customizable
- Expanding library of objects

### Effects
- 36 procedural, customizable, animatable effects
- 12 categories including Background, Foreground, Impact, Reaction, Trails and more
- Effects include: Speed Lines, Action Backgrounds, Heat Refraction, Light Trails and more

### Node Groups
- 26 2K Traditional Art Textures
- 23 2K Foliage Alpha Textures
- Utility Nodes for Stepped Motion (animating on 2s, 4s) and LFO (easily add oscillating motion)
- Main and Asset Shaders available as Node Groups for easy editing
