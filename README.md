# The Waiting Room Assets
![banner2](https://github.com/user-attachments/assets/417c1e47-0eba-47c6-b779-34fbea1a4710)
This contains all source 3D models and textures for The Waiting Room. 

# Requirements
- Autodesk 3ds Max 2025 (Not anything older)
- Adobe Substance 3D Painter 11.0.1 (Not anything older)
- Adobe Photoshop 2025
- 5GB of free storage
- 64 GB of RAM for concurrent application usage
- 24GB of VRAM for texture export and NRML, WSNRML, RGH, HGT, AO map baking
- A CUDA-powered GPU (RTX 3090, RTX 4090, or RTX 5090 is recommended). AMD GPUs are **NOT** supported for baking or rendering in industry standard pipelines due to lack of OpenCL development from AMD.

# Directory structure
📂3ds Max (contains the 3ds Max project file for the 3D model)<br />
📂Decals (contains the Photoshop PSD and exported PNGs for various decals)<br />
📂SPP (contains the Substance Painter Project (SPP) files for texture editing and export)<br />

# Important notes
- This repository will go over the 2GB push limit for GitHub. When creating a new branch, split the SPP directory into two to allow for the entire repository to be pushed.
- This repository may require extra LFS storage due to the large repository size.
- The objects are not to scale or placed properly with the Unity scene. Many objects were rescaled and moved in the final Unity scene. Refer to the Unity scene for proper placement.
- None of the objects have materials assigned, so edits to materials or map assignments will be done in Unity.
- Objects are modelled at a **low LOD** to reduce memory overhead, drawcalls, and filesize.
- Override with Fast Shader is enabled by default in the Max file. Switch to OFF to disable culling of backfaces.
- The object's scale is in **meters**. 
