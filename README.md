# Compute Shader Mesh Path Tracing
Path tracing engine to raytrace meshes from Unity gameObjects. Implemented using HLSL compute shaders in Unity3D.

**Currently implemented:**
- Opaque materials.
- Pathtracing for perfect planes and spheres.
- Phong specular reflections.
- Lambert diffuse relections.
- Importance sampling to speed-up convergence.
- Pathtracing for meshes from Unity gameObjects.
- Normal interpolation using barycentric coordinates.

**To do:**
- Non-opaque materials.
- Directional lights + multi-importance sampling.

# Screenshots

<img src="https://raw.github.com/akoreman/Compute-Shader-Mesh-Ray-Tracing/main/images/SpecReflections.PNG" width="400">  

<img src="https://raw.github.com/akoreman/Compute-Shader-Mesh-Ray-Tracing/main/images/Geometry.PNG" width="400">  

**Normal interpolation visualised by interpolating vertex colors.**

