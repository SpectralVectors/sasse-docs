---
title: Specialty Shaders
description: List of SASSE Library Materials and Shaders.
layout: libdoc/page

category: Materials
order: 400
---
- Genga
{:toc}

## Genga
![Genga](/assets/Materials/Base_Shaders/SASSE_Genga_Preview.png)
### Settings
- **Highligh Color** - color to shade the lit areas
- **Shadow Color** - color to shade the dark areas
- **Highlight / Shadow** - light threshold
- **Stripe / Solid** - mix between solid and striped lines for the lit areas
- **Stripe Scale** - scale of the stripes
- **Stripe Distortion** - distort the stripes - _a little distortion can add a hand-drawn feel_

## Halftone
![Halftone](/assets/Materials/Base_Shaders/SASSE_Halftone_Preview.png)
### Settings
- **Base Color / Texture** - base material color
- **Light Bands Count** - sensitivity to light
- **Rim Light** - highlight wrap
- **Ambient Occlusion** - mix in Ambient Occlusion for an airbrushed look
- **AO Depth** - how dark is the Ambient Occlusion
- **Shadow Depth** - how dark is the shadow - _1 is fully black_
- **Dots Scale** - size of the halftone dots
- **Shader Strength** - how bright / intense is the shader overall - _0 is black, 1 is standard shading, higher values are emissive_
- **Surface Amount** - surface bumps on dots
- **Light Band Amount** - light band bumps on dots
- **Rim Light Amount** - rim light bumps on dots

## Holofoil
![Holofoil](/assets/Materials/Base_Shaders/SASSE_Holofoil_Preview.png)

## Outline
![Outline](/assets/Materials/Base_Shaders/Toon_Outline_Preview.png)

## Retro / Grain
![RetroGrain](/assets/Materials/Base_Shaders/SASSE_RetroGrain_Preview.png)
### Settings
- **Base Color / Texture** - set the main base color or texture, this will also determine shadow and highlight color in combination with Scene lighting
- **Light Band Threshold** - both the number of lightbands and the object's sensitivity to light
- **Roughness** - how the light is dispersed across the object
- **Rim Light Strength** - how bright / intense is the highlight
- **Rim Light Mask** - does the highlight appear all around the object, or only where the light hits
- **Ambient Occlusion** - mix in Ambient Occlusion for an airbrushed look
- **AO Depth** - how dark is the Ambient Occlusion
- **Shadow Depth** - how dark is the shadow - _1 is fully black_
- **Shader Strength** - how bright / intense is the shader overall - _0 is black, 1 is standard shading, higher values are emissive_
- **Surface Input** - Bump map texture input (Surface Normals)
- **Surface Amount** - Bump strength
- **Light Band Input** - light band distortion input
- **Light Band Amount** - distortion strength
- **Rim Light Input** - highlight distortion input
- **Rim Light Amount** - distortion strength

## Tears / Sweat
![Tears](/assets/Materials/Base_Shaders/Tears_Sweat_Preview.png)
### Settings
- **Color** - highlight tint
- **Roughness** - dispersion of highlight
- **Bump Strength** - depth of the bumps
- **Bump Scale** - width of the bumps
- **Bump Driver** - animate bump motion
