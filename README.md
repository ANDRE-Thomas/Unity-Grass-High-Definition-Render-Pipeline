# Unity Grass High Definition Render Pipeline
 A high-performance grass rendering utility for Unity's HDRP.

In this side project, I aimed to create a grass shader that can be used over a very large area while still maintaining high visual fidelity by utilizing all the features available in Unity's High Definition Render Pipeline. All of this while ensuring high performance (60+ fps) on high and mid-range hardware and playable performance (30+ fps) on low-end hardware.

## Visuals

### Render distance and density
https://user-images.githubusercontent.com/64555596/224430086-66e5e4b5-62ed-46cd-a6d3-e1fa20fc7b7b.mp4

### Lighting
https://user-images.githubusercontent.com/64555596/224430442-825be6a2-b1f2-430c-9b92-7019c8b56b26.mp4

## Currently implemented features
* Rendering of tens of millions of individual grass blades
* High graphical fidelity by utilizing the light loop system of the HDRP, enabling this shader to have accurate lighting on each individual grass blade.
* LOD system controlling the density and mesh LOD of the grass to maintain high performance.

## Planned Features
* Grass collision, enabling each grass blade to be affected by physical objects.
* Modification of the individual properties of grass blades (color, length, rigidity...) using multiple textures.
* General performance and API improvements.

## Usage
This repository currently contains no code as it is still a work in progress, and I plan on potentially using this grass in one of my games. If this game is released or canceled, I will then make the code of this project publicly available, and you will be able to use it as a learning resource.
