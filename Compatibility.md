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

### Compatible with Blender 4 and higher

It will work with 3.6 LTS, though many sockets need to be manually reconnected in Geometry Node trees, and will likely experience issues on earlier versions due to the rapid changes in Geometry Nodes upon its introduction.

_If there is demand for a 3.6 compatible version, I can prepare and test an alternate release._

Shaders and non-Geometry Nodes based objects should work back to 2.93, and many objects could have their Geometry Nodes modifiers applied in 3.6 and then imported to 2.93, but you would lose much of the customization that makes the objects and effects function.
