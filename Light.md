---
title: Light
description: List of SASSE Library Effects.
layout: libdoc/page

category: Effects
order: 200
---
- Light
{:toc}

## Classic Flare Plane
![Classic Flare](/assets/Effects/Light/Kanada_Flare_Preview.png)
### Material
- **Color** - base color

### Motion
- **Progress** - animate transparency, scale, rotation and textures

## Light Beam Plane
![Light Beam Plane](/assets/Effects/Light/Light_Beam_Plane_Preview.png)
- **Color** - base color of light beam
- **Beam Start Offset** - move beam start vertex group
- **Beam End Offset** - move beam end vertex group
- **Taper Factor** - amount to shrink one end of plane

## Light Halo Plane
![Light Halo Plane](/assets/Effects/Light/Light_Halo_Plane_Preview.png)
- **Color** - base color
- **Beam Start Offset** - move one end of the light halo plane
- **Beam End Offset** - move the other end of the light halo plane
- **Taper Factor** - amount to shrink one end of plane 
- **Blend** - mix between outer and inner halo

## Sparkles
![Sparkle Plane](/assets/Effects/Light/Sparkle_Plane_Preview.png)
- **Collection** - collection holding sparkle planes
- **Align Camera** - Camera for the planes to face
- **Offset** - move the sparkle planes
- **Scale** - size of the planes
- **Seed** - randomize effect
- **Randomize by Time** - animate location of sparkles over time
- **Randomize Rate** - rate of sparkle shift
- **Pulse Rate** - rate of sparkle scale up and down
- **Pulse Depth** - how much to scale the sparkle planes
- **Pulse Offset** - offset the scale if too small / large
