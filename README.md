# SmolEngine SDK
![SmolEngine](https://i.imgur.com/CHIJC3m.png)
# Level Editor
![SmolEngine](https://i.imgur.com/bKSFaLY.png)
![SmolEngine](https://i.imgur.com/h8k6VL3.png)

<p align="center"> <img src="https://media.giphy.com/media/05n8je7Inq6EsMAxsn/giphy.gif" width="720" height="420" /> </p>

## Features
### Rendering
- [x] RTX Direct Illumination [(RTXDI)](https://developer.nvidia.com/rtxdi)
- [x] [ReLAX](https://developer.nvidia.com/nvidia-rt-denoiser) Real-Time Denoiser
- [x] Deep Learning Super Sampling [(DLSS)](https://www.nvidia.com/de-de/geforce/technologies/dlss/)
- [x] FidelityFX Super Resolution [(FSR)](https://www.amd.com/en/technologies/radeon-software-fidelityfx-super-resolution)
- [x] [Dear ImGUI](https://github.com/ocornut/imgui) integration
- [x] Own abstraction layer on top of Vulkan API
- [x] In-Game UI (text, buttons, input fields, etc)
- [x] Raytracing/Graphics/Compute pipelines
- [x] Full GLSL/HLSL support
- [x] Post-Processing: Bokeh Depth of Field, Bloom
- [x] UE4 Sky Atmosphere
- [x] Direct and Indirect Lighting
- [ ] RTX Global Illumination [(RTXGI)](https://developer.nvidia.com/rtxgi)
- [ ] Animations
- [ ] Geometry lights
- [ ] Scriptable pipeline
- [ ] Mesh shaders
- [ ] Particle system
- [ ] VR support

### Core

- [x] C#/C++ Scripting API
- [x] Entity Component System
- [x] Jobs System
- [x] Prefabs
- [x] Audio
- [x] Level Editor
- [x] Physics: 2D ([Box2D](https://github.com/erincatto/box2d)), 3D ([Bullet3](https://github.com/bulletphysics/bullet3))
- [x] Profilers: [Optick](https://github.com/bombomby/optick), [Nsight Graphics](https://developer.nvidia.com/nsight-graphics/)
- [x] C++ 20
- [ ] Networking
- [ ] Pathfinding
- [ ] Docs

## Requirements
- Ray tracing capable GPU (RTX 20 series or higher)
- Visual Studio 2022 (full C++20 support)
- Windows 10 or higher
- Python 3.x and [gdown](https://github.com/wkentaro/gdown) package: ```pip install gdown```

## Limitations
- Developed by one person for learning purposes
- At a very early stage, unstable API
- No source code at the moment
- No documentation

## Extensions
- VK_KHR_16BIT_STORAGE_EXTENSION_NAME
- VK_KHR_SHADER_FLOAT16_INT8_EXTENSION_NAME
- VK_KHR_ACCELERATION_STRUCTURE_EXTENSION_NAME
- VK_KHR_RAY_TRACING_PIPELINE_EXTENSION_NAME
- VK_KHR_BUFFER_DEVICE_ADDRESS_EXTENSION_NAME
- VK_NVX_BINARY_IMPORT_EXTENSION_NAME
- VK_NVX_IMAGE_VIEW_HANDLE_EXTENSION_NAME
### Debug builds
- VK_NV_DEVICE_DIAGNOSTIC_CHECKPOINTS_EXTENSION_NAME
- VK_NV_DEVICE_DIAGNOSTICS_CONFIG_EXTENSION_NAME

## Download SDK
1. Install [Vulkan SDK](https://vulkan.lunarg.com/sdk/home#windows)
2. Clone the repository: ```git clone https://github.com/Floritte/SmolEngine-SDK```
3. Run `scripts/download_sdk.bat` to download SDK installer
4. Run `editor/SmolEngine-Editor.exe`

The Sponza scene is located in the tests folder.
