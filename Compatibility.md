---
title: Compatibility
description: More information about Blender version compatibility
layout: libdoc/page

category: FAQ
order: 600
---
- Compatibility
{:toc}

## Compatibility
SASSE was designed to take advantage of Geometry Nodes and the tight integration it provided between shaders, animation and mesh editing, and, as such, works best in more recent versions of Blender.

Compatibility is guaranteed and fully tested in Blender 4+. 

It should work with 3.6 LTS (testing is on-going), and will likely experience issues on earlier versions due to the rapid changes in Geometry Nodes upon its introduction.

Shaders and non-Geometry Nodes based objects should work back to 2.8, and many objects could have their Geometry Nodes modifiers applied in 3.6 and then imported to 2.8, but you would lose much of the customization that makes the objects and effects function.
