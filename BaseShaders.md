---
title: Base Shaders
description: List of SASSE Library Materials and Shaders.
layout: libdoc/page

category: Materials
order: 400
---
- Toon Diffuse / General
{:toc}

## Diffuse / General
![Diffuse](/assets/Materials/Base_Shaders/SASSE_DiffuseGeneral_Preview.png)
### Settings
- **Base Color | Texture** - set the main base color or texture, this will also determine shadow and highlight color in combination with Scene lighting
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

## Glossy / Metallic
![Glossy](/assets/Materials/Base_Shaders/SASSE_GlossyMetallic_Preview.png)
### Settings
- **Base Color | Texture** - set the main base color or texture, this will also determine shadow and highlight color in combination with Scene lighting
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

## Specular / Wet
![Specular](/assets/Materials/Base_Shaders/SASSE_SpecularWet_Preview.png)
### Settings
- **Base Color | Texture** - set the main base color or texture, this will also determine shadow and highlight color in combination with Scene lighting
- **Specular Color | Texture** - set the highlight tint
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

## Glass / Bubble
![Glass](/assets/Materials/Base_Shaders/SASSE_GlassBubble_Preview.png)
### Settings
- **Base Color** - set the main base color, this will also determine shadow and highlight color in combination with Scene lighting
- **IOR** - the index of refraction for the glass
- **Roughness** - how the light is dispersed across the object
- **Fog** - frosted glass effect - _based on Ambient Occlusion_
- **Transparency** - the glass opacity
- **Surface Input** - Bump map texture input (Surface Normals)
- **Surface Amount** - Bump strength

## Transparent
![Transparent](/assets/Materials/Base_Shaders/SASSE_Transparent_Preview.png)
### Settings
- **Base Color | Texture** - set the main base color or texture, this will also determine shadow and highlight color in combination with Scene lighting
- **Light Band Count** - both the number of lightbands and the object's sensitivity to light
- **Rim Light** - how bright / intense is the highlight
- **Shadow Depth** - how dark is the shadow - _1 is fully black_
- **Transparency** - opacity of the object
- **Surface Input** - Bump map texture input (Surface Normals)
- **Surface Amount** - Bump strength
- **Light Band Input** - light band distortion input
- **Light Band Amount** - distortion strength
- **Rim Light Input** - highlight distortion input
- **Rim Light Amount** - distortion strength
