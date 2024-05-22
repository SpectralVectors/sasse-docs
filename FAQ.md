---
title: FAQ
description: Frequently Asked Questions
layout: libdoc/page

category: FAQ
order: 600
---
- FAQ
{:toc}

## FAQ
### Why aren't the Ambient Occlusion settings doing anything?
Make sure you have enabled Ambient Occlusion in your Render Settings.

### Why are the colors faded / washed out?
Make sure you are using Standard View Transform under Color Management in your Render Settings.

### Why isn't _______ Effect working? I put it in my scene and nothing happened!?!
Most Assets and Effects can be simply dropped into your scene, but some depend on existing objects, e.g.:
- Electric Sphere and Impact Cracks require an object to Shrinkwrap to
- Trails require a 'Follow Object' that must be animated (or at least move while the Timeline is running)
- Many Assets can be supplied an 'Align Camera' so that they are always facing the correct direction
- Heat Ripple Plane requires a Reflection Capture

### The highlights on my object turned black, what's going on?
I wanted to preserve the ability to get an almost Emissive / Bloom effect out of the Rim Light by pushing the value very high.

As a consequence, lights can 'overload' the Rim Light if they are too bright or too close.

To resolve this, open the Node Group and click 'Clamp' on the 'Multiply' node in the 'Fresnel / Highlight' frame.

This will prevent highlights from going black, but will also remove the Emissive / Bloom effect.

I am investigating ways to address this issue that preserve functionality without having to edit a node graph.

### I'm using the Individual Asset Shaders, why are my objects black?
See [IndividualAssetShaders](https://spectralvectors.github.io/sasse-docs/IndividualAssetShaders.html)

### Why are my outlines / inner lines too thick / too thin / not showing up at all?
Make sure that you apply the scale to the object you are adding lines to.

If an object is scaled to 0.001, then you may need a line thickess of 1000 in order to see them.

Or, if an object is scaled up, you may need a much smaller scale to avoid covering your entire mesh in black.

### Why aren't the 'seamless' textures seamless on my object?
The seamless textures are seamless from bottom to top and left to right, but depending on how they are mapped onto your object, they may not perfectly align at every intersection.

To work around this issue you can:
- move, scale or rotate the texture to place the artifacts in less noticeable areas
- combine multiple rotated copies of the texture
- use projection mapping

### How do you use Surface, Light Band and Rim Light Inputs and Amounts?
If you just turn up or down these settings on the Shaders you may not see any change.

The Inputs are designed to have textures connected to them (SASSE Seamless Textures, Blender procedural textures, or any of your choosing), with the Amount controlling the strength of the effect.

Surface will have a 'Bump' or surface Normal appearance, which works well for bumps, wear and damage, but can appear very 3D.

Light Band will control the profile of the lines separating each color band, which works well for simulating brush strokes, and can be animated for a hand-painted look.

Rim Light works the same way as the Light Band control, only a little more subtle

### Why doesn't _____ Color light show up as bright as the others?
One limitation of the colored light toon shader system is that certain colors on your objects can appear to 'swallow' certain colors of light.

A workaround for this is to avoid fully saturated colors on your objects. 

Even slightly desaturating an object's base color can improve the intesity of a light's color.
