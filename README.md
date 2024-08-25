# Planar Reflections
### Planar reflections for Unity’s Universal Render Pipeline.

![alt text](https://github.com/dead-folk/planar-reflections/wiki/Images/Home00.png?raw=true)
*An example of global and local reflections.*

A system for defining and rendering planar reflection cameras in Unity's Universal Render Pipeline. It supports **Global** mode, where a single reflection camera can be used across an entire scene (useful for water and other large reflective surfaces) and **Local** mode, where a list of **Renderers** can be defined to receive reflections (useful for smaller surfaces like wall mirrors).

Refer to the [Wiki](https://github.com/dead-folk/planar-reflections/wiki/Home) for more information.

## Instructions
- Open your project manifest file (`MyProject/Packages/manifest.json`).
- Add `"com.deadfolk.planarreflections": "https://github.com/dead-folk/planar-reflections.git"` to the `dependencies` list.
- Open or focus on Unity Editor to resolve packages.

## Requirements
- Unity 2022.3.0f3 or higher.