# Showcase

Showcase and collection of projects

## Contents

- [Showcase](#showcase)
  - [Contents](#contents)
  - [AI](#ai)
    - [Image Caption Node for ComfyUI](#image-caption-node-for-comfyui)
    - [Prompt Generator Node For ComfyUI](#prompt-generator-node-for-comfyui)
    - [AAML (Anti Aliasing with Machine Learning)](#aaml-anti-aliasing-with-machine-learning)
  - [Animation](#animation)
    - [Maya](#maya)
  - [CUDA](#cuda)
    - [Julia](#julia)
    - [Path Tracer](#cuda-path-tracer)
  - [Game Engines (Unity and Unreal Engine)](#game-engines--unity-and-unreal-engine)
    - [Unreal Engine](#unreal-engine)
      - [Third Person Shooter Game](#third-person-shooter-game)
    - [Unity](#unity)
      - [Bullet Hell](https://github.com/TeamWololo/BulletHell_Repo)
      - [Lighting](#lighting)
      - [Ray Tracing (with Compute Shader)](#ray-tracing-with-compute-shader)
  - [Graphic APIs](#graphic-apis)
    - [OpenGL](#opengl)
      - [Ray Casting and Ray Tracing](#ray-casting-and-ray-tracing)
      - [Particle Simulation with Compute Shader](#particle-simulation-with-compute-shader)
      - [Programmable Vertex Pulling (PVP)](#programmable-vertex-pulling-pvp)
      - [VR](#vr)
      - [PBR](#pbr)
      - [SSAO](#ssao)
      - [Water Simulation](#water-simulation)
      - [Cloud Animation](#cloud-animation)
      - [Leaves Animation](#leaves-animation)
      - [Shockwave](#shockwave)
      - [Volumetric Ice](#volumetric-ice)
      - [Cloth Shading](#cloth-shading)
      - [Distortion Shader](#distortion-shader)
      - [Flipbook](#flipbook)
      - [Small solar system](#small-solar-system)
    - [Vulkan](#vulkan)
      - [Import Model](#import-model)
  - [Ray Tracing](#ray-tracing)
    - [RayTracing-Peter Shirley with ISPC Language](https://github.com/alpertunga-bile/ps_ray_trace)
    - [RayTracing-PeterShirley](#raytracing-petershirley)
      - [Ray Tracing In One Weekend Final](#ray-tracing-in-one-weekend-final)
      - [Motion Blur](#motion-blur)
      - [Earth Texture](#earth-texture)
      - [Diffuse Light](#diffuse-light)
      - [Standart Cornell Box](#standart-cornell-box)
      - [Ray Tracing In One Week Final](#ray-tracing-in-one-week-final)
      - [10 Rays Standart Cornell Box with Monte Carlo](#10-rays-standart-cornell-box-with-monte-carlo)
      - [Ray Tracing Rest Of Your Life Final](#ray-tracing-rest-of-your-life-final)
    - [CUDA Path Tracer](#cuda-path-tracer)
  - [Tools](#tools)
    - [Markdown Parser and Parser Tools](#markdown-parser-and-parser-tools)
    - [AI Upscale](#ai-upscale)
    - [Wrap Gradio](https://github.com/alpertunga-bile/wrap_gradio)
    - [Differential Diffusion Gradio Example](https://github.com/alpertunga-bile/differential-diffusion_gradio_example/blob/gradio_example/examples/gradio/gradio_example.md)
    - [Auto CMake](https://github.com/alpertunga-bile/auto-cmake)
    - [Video Upscale](https://github.com/alpertunga-bile/video-upscale)
    - [PixelDancer](https://github.com/alpertunga-bile/PixelDancer)
    - [Third Wheel](https://github.com/alpertunga-bile/third_wheel)
    - [Auto Civitai Cpp](https://github.com/alpertunga-bile/auto-civitai-cpp)
    - [Resource Lists (Repository)](https://github.com/alpertunga-bile/link_list)
    - [simdjson_python](https://github.com/alpertunga-bile/simdjson_python)
    - [Auto Civitai Rust](https://github.com/alpertunga-bile/auto_civitai_rs)
    - [LZString](https://github.com/alpertunga-bile/lz-string)
    - [Memory Pool](https://github.com/alpertunga-bile/PXD-memory-pool)
  - Web
    - [Cacher WASM](https://github.com/alpertunga-bile/cacher_wasm)
    - [Civitai Viewer](https://github.com/alpertunga-bile/civitai_viewer)
    - [Web Testbed](https://github.com/alpertunga-bile/web_testbed)
  - [References](#references)

## AI

### Image Caption Node for ComfyUI

- [Repository](https://github.com/alpertunga-bile/image-caption-comfyui)

![image_caption_node_basic_workflow](https://github.com/alpertunga-bile/image-caption-comfyui/blob/master/images/basic_workflow_with_promp_generator.png?raw=true)

![image_caption_node_basic_workflow_2](https://github.com/alpertunga-bile/image-caption-comfyui/blob/master/images/basic_workflow_with_prompt_generator_2.png?raw=true)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

### Prompt Generator Node For ComfyUI

- [Repository](https://github.com/alpertunga-bile/prompt-generator-comfyui)

![basic_workflow](https://github.com/alpertunga-bile/prompt-generator-comfyui/blob/master/images/basic_workflow.png)

![hires_workflow](https://github.com/alpertunga-bile/prompt-generator-comfyui/blob/master/images/hires_workflow.png)

### AAML (Anti Aliasing with Machine Learning)

- [Repository](https://github.com/alpertunga-bile/AAML)

|                                                    Original                                                    |                                           Row By Row by 3x3 filter                                            |                                            Full Image by 3x3 filter                                            |
| :------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: |
| ![test](https://user-images.githubusercontent.com/76731692/210861435-ad89748d-e9e8-4989-bbd5-3ca8c0e45ca6.jpg) | ![row](https://user-images.githubusercontent.com/76731692/226137407-87d57af2-be17-4c87-a27e-a9a083900c99.png) | ![full](https://user-images.githubusercontent.com/76731692/226137447-5d70e594-8804-4762-ae1c-631996f91f03.png) |

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

## Animation

### Maya

![bouncingBall](https://user-images.githubusercontent.com/76731692/153717834-9780b3ba-28e2-490e-856c-4f8e31208b1f.gif)

![bouncingBalls](https://user-images.githubusercontent.com/76731692/153717898-0bc32aa5-1ee0-4bb9-8324-f406d7523198.gif)

![roboticArm_1](https://user-images.githubusercontent.com/76731692/153717879-91b5b2b9-b462-4b64-b387-f8f0588f7456.gif)

![myRobotProject](https://user-images.githubusercontent.com/76731692/153718094-f95d8f29-bf11-4d41-a524-9dbf45c3937d.gif)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

## CUDA

### Julia

![julia](CUDA_outputs/julia.png)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

## Game Engines ( Unity and Unreal Engine)

### Unreal Engine

#### Third Person Shooter Game

- Gameplay - <https://youtu.be/hJrapZHp0Lw>

- Weapons & Death Animation - <https://youtu.be/aFnYuMMqtxQ>

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

### Unity

#### Lighting

![bakedGI](https://user-images.githubusercontent.com/76731692/144286416-1bd551de-f3b6-40c0-b824-a46222239caa.png)

<https://user-images.githubusercontent.com/76731692/144286509-7999a63c-8e52-4930-87a1-447299b673f1.mp4>

![scifiCorridor](https://user-images.githubusercontent.com/76731692/144286539-2941216b-e4f1-43a2-85e2-82700442556d.png)

#### Ray Tracing (with Compute Shader)

![reflection](https://user-images.githubusercontent.com/76731692/126897641-c8acef57-1668-4c3d-bcf1-417783df4864.jpg)

![lambert_phong_final](https://user-images.githubusercontent.com/76731692/126897643-9222aa89-eb3f-42e5-a637-8cd141363a54.jpg)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

## Graphic APIs

### OpenGL

#### Ray Casting and Ray Tracing

![raycasting_Texture](https://user-images.githubusercontent.com/76731692/131123299-7605ca17-3d82-49d5-8fba-f048a20e5926.jpg)

![raycasting_Texture_Plane](https://user-images.githubusercontent.com/76731692/131123304-dcb8be36-1eed-4946-8ae6-facb8bf794f6.jpg)

![raytracing_Reflection](https://user-images.githubusercontent.com/76731692/131123330-822040fb-aa58-4846-9710-1b2000155632.jpg)

#### Particle Simulation with Compute Shader

![blackHole](https://user-images.githubusercontent.com/76731692/143777566-945ef8f8-b775-4498-a9f9-5326621bef02.png)

#### Programmable Vertex Pulling (PVP)

![dragon_pvp](https://user-images.githubusercontent.com/76731692/143930665-e9807170-4565-45bd-b1c3-4cd657fcd185.png)

#### VR

![anaglyph_rendering](https://user-images.githubusercontent.com/76731692/131123380-d8a01960-b73f-45e7-9614-6283887b7573.jpg)

#### PBR

![pbr_hdr_cubemap](https://user-images.githubusercontent.com/76731692/126897608-a9c7a7ec-664c-47c2-b821-76a559ffdc4d.jpg)

![pbr_model](https://user-images.githubusercontent.com/76731692/131123133-70bc3b2c-6318-4bc1-8163-c5a0dc6f8cf7.jpg)

#### SSAO

![ssao](https://user-images.githubusercontent.com/76731692/126897611-c18b810c-0807-4f74-a3a2-addc8dab6739.jpg)

![dragon_ssao](https://user-images.githubusercontent.com/76731692/127374087-34fc474f-eb80-4839-8416-769324782f0b.jpg)

#### Water Simulation

<https://user-images.githubusercontent.com/76731692/129045001-8f2fc31e-a014-4b36-8232-f1efd064be0b.mp4>

#### Cloud Animation

<https://user-images.githubusercontent.com/76731692/129045118-6b22b7a0-2718-4a1a-84d5-d213d9fb158d.mp4>

#### Leaves Animation

<https://user-images.githubusercontent.com/76731692/131123717-217511fa-fd9c-4953-b7e9-cabb12836354.mp4>

#### Shockwave

<https://user-images.githubusercontent.com/76731692/133923190-b228d0de-1ffc-4f2b-9a3d-76fe5798ab2a.mp4>

#### Volumetric Ice

![volumetric_ice](https://user-images.githubusercontent.com/76731692/131123781-22504c4b-9106-4e84-82f6-f126f7fc140c.jpg)

#### Cloth Shading

![cotton_cloth_shading](https://user-images.githubusercontent.com/76731692/131123515-67b7e117-e7eb-4f76-b52a-6e68dfd1f71d.jpg)

#### Distortion Shader

<https://user-images.githubusercontent.com/76731692/131123549-297861e1-f1a9-4f75-9d5e-33b0330b337f.mp4>

#### Flipbook

<https://user-images.githubusercontent.com/76731692/131123603-46637d3b-dc16-4989-a882-f6c137b37a78.mp4>

#### Small solar system

<https://user-images.githubusercontent.com/76731692/126897596-b8571020-fa80-4422-b252-b7249d0a888d.mp4>

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

### Vulkan

#### Import Model

![hello_model](https://user-images.githubusercontent.com/76731692/126897626-54ef1208-c087-4402-b522-2c6f0500c1a6.jpg)

![minecraft_output](https://github.com/alpertunga-bile/Showcase/assets/76731692/17dfa00f-a853-4693-8e27-e87c75f9ae63)

![imgui](https://github.com/alpertunga-bile/Showcase/assets/76731692/171b3a73-d844-41f3-a910-c418e269cf3c)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

## Ray Tracing

### RayTracing-PeterShirley

#### Ray Tracing In One Weekend Final

![raytracinginoneweekend](https://user-images.githubusercontent.com/76731692/131985372-ecfce2bb-b6f9-4ecb-85db-d8eb6e9a65d1.jpg)

#### Motion Blur

![motion_blur](https://user-images.githubusercontent.com/76731692/131985486-8767e9d8-8d18-4276-833e-883dac990b28.jpg)

#### Earth Texture

![earth_texture](https://user-images.githubusercontent.com/76731692/131986027-9aef51d4-4a3a-43fc-9447-87c5525e27ca.jpg)

#### Diffuse Light

![diffuseLight](https://user-images.githubusercontent.com/76731692/131986048-046ea9bf-4449-436e-beda-5e4420a919f9.jpg)

#### Standart Cornell Box

![standartCornellBox](https://user-images.githubusercontent.com/76731692/131986096-8de71b14-a1c3-48b0-b85c-a6f06a9617df.jpg)

#### Ray Tracing In One Week Final

![raytracinginoneweekFinal](https://user-images.githubusercontent.com/76731692/131986178-491a61cb-809a-4a15-ad3a-556666904411.jpg)

#### 10 Rays Standart Cornell Box with Monte Carlo

![MC_pdf_10Rays](https://user-images.githubusercontent.com/76731692/131986246-bb323277-8817-4bcf-aa45-f41d9a8714fc.jpg)

#### Ray Tracing Rest Of Your Life Final

![raytracingrestofyourlifeFinal](https://user-images.githubusercontent.com/76731692/133923289-b2243c63-123c-4a3a-8a67-f6aa46a8856b.jpg)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

### CUDA Path Tracer

![bunny_diffuse](CUDA_outputs/bunny_diffuse.png)

![bunny_refraction](CUDA_outputs/bunny_refraction.png)

![bunny_specular](CUDA_outputs/bunny_specular.png)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

## Tools

### Markdown Parser and Parser Tools

- [Repository](https://github.com/alpertunga-bile/prompt-markdown-parser)
- Model Name : gpt2
- Min Length : 10
- Max Length : 50
- Features are off
- Recursive Level : 1
- Seed : goddess
- Self Recursive : Off
- Generated Prompt : goddess, (intricate detailed skin texture:1.2), (electric spark, broken machine:1.1), (machine body:1.2), looking at the viewer, (smart sharpen:1.2), medium breasts, (Ghost in the Shell), depth of field, gradient background, backlit, rim lighting, dramatic lighting, ambient occlusion, volumetric lighting, professional studio lighting, closed mouth, insanely detailed,, ((masterpiece)), absurdres, HDR

![00001-1760621993](https://user-images.githubusercontent.com/76731692/235329508-e33b0d29-c72f-4b12-8e1b-11b35e45dedc.png)

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

### AI Upscale

- [Repository](https://github.com/alpertunga-bile/AIUpscaleGUI)

|                                                          512x512                                                           |                                                           2048x2048                                                            |
| :------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: |
| ![00024-3324991962](https://user-images.githubusercontent.com/76731692/233845862-bc77ede8-421b-4076-a31d-29b5ba4f109d.png) | ![00024-3324991962_out](https://user-images.githubusercontent.com/76731692/233845891-49a4df16-82b1-409e-bcea-2fdeac65044e.png) |

[Back To Top](https://github.com/alpertunga-bile/Showcase#showcase)

## References

- Gordon V.S., & Clevenger J.(2020). Computer Graphics Programming in OpenGL with C++ (2nd ed.). Mercury Learning and Information
- Vries J.(2020). Learn OpenGL: Learn modern OpenGL graphics programming in a step-by-step fashion(1st ed.). Kendall & Welling
- Wolff D.(2018). OpenGL 4 Shading Language Cookbook: Build high-quality, real-time 3D graphics with OpenGL 4.6, GLSL 4.6 and C++17(3rd ed.). Packt Publishing.
- Kosarevsky S., & Latypov V.(2021). 3D Graphics Rendering Cookbook: A comprehensive guide to exploring rendering algorithms in modern OpenGL and Vulkan(1st ed.). Packt Publishing.
- GPU Ray Tracing in Unity. <http://three-eyed-games.com/2018/05/03/gpu-ray-tracing-in-unity-part-1/>
- Ben Cloward's Youtube Tutorials. <https://www.youtube.com/user/bcloward>
- CgShow's Youtube Tutorials. <https://www.youtube.com/user/asif786ali1>
