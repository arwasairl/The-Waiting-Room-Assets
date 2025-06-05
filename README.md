# The Waiting Room Assets
This contains all source 3D models and textures for The Waiting Room. 

# Requirements
- Autodesk 3ds Max 2025 (Not anything older)
- Adobe Substance 3D Painter 11.0.1 (Not anything older)
- Adobe Photoshop 2025
- 64 GB of RAM for concurrent application usage
- 24GB of VRAM for texture export and NRML, WSNRML, RGH, HGT, AO map baking
- A CUDA-powered GPU (RTX 3090, RTX 4090, or RTX 5090 is recommended). AMD GPUs are **NOT** supported for baking or rendering in industry standard pipelines due to lack of OpenCL development from AMD.

# Directory structure
📂3ds Max (contains the 3ds Max project file for the 3D model)
📂Decals (contains the Photoshop PSD and exported PNGs for various decals)
📂SPP (contains the Substance Painter Project (SPP) files for texture editing and export)

# Important notes
- The objects are not to scale or placed properly with the Unity scene. Many objects were rescaled and moved in the final Unity scene. Refer to the Unity scene for proper placement.
- None of the objects have materials assigned, so edits to materials or map assignments will be done in Unity.
- Objects are modelled at a **low LOD** to reduce memory overhead, drawcalls, and filesize.
- Override with Fast Shader is enabled by default in the Max file. Switch to OFF to disable culling of backfaces.
- The object's scale is in **meters**. 
