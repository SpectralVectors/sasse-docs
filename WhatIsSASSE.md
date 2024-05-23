---
title: What Is The SASSE Library?
description: Introduction to SASSE
layout: libdoc/page

category: Introduction
order: 0
---
- What Is The SASSE Library?
{:toc}
## What Is The SASSE Library?
The SASSE Library is a series of shaders, assets, effects and utilities designed to give you fast, high-quality stylized renders.

SASSE stands for Stylized Assets, Spectral Shaders and Effects.

It is an evolution of an [earlier addon](https://github.com/SpectralVectors/GhibliGenerator) of mine, designed to take advantage of Blender's Asset Browser and Geometry Nodes to give you easily accessible, procedural and customizable stylized assets and effects.

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


And using the latest Blender tool, Geometry Nodes:
- Draw objects into your scene, like chains, beams, ropes, cables or lightning!
- Quickly access all object and shader options from a single modifier!
- Procedural textures, geometry, and animations!

This led to the development of SASSE.
