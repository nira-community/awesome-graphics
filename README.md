# Computer Graphics Programming Resources

List of freely available resources to study computer graphics programming.

## Table of Contents
- [Learning Path](#learning-path)
- [Foundations](#foundations)
  - [Getting Started](#getting-started)
  - [C++](#c)
  - [Mathematics](#mathematics)
- [Graphics Fundamentals](#graphics-fundamentals)
  - [Overview](#overview)
  - [Courses](#courses)
  - [Software Rendering](#software-rendering)
- [GPU Fundamentals](#gpu-fundamentals)
  - [GPU Architecture](#gpu-architecture)
  - [Shaders](#shaders)
- [Graphics APIs](#graphics-apis)
  - [OpenGL](#opengl)
  - [Vulkan](#vulkan)
  - [DirectX 11](#directx-11)
  - [DirectX 12](#directx-12)
  - [Metal](#metal)
  - [WebGL](#webgl)
  - [WebGPU](#webgpu)
  - [Tooling (Debuggers)](#tooling-debuggers)
- [Rendering Techniques](#rendering-techniques)
  - [Renderer Architecture](#renderer-architecture)
  - [Geometry, Culling and LOD](#geometry-culling-and-lod)
  - [Materials and Shading](#materials-and-shading)
  - [Lighting and Shadows](#lighting-and-shadows)
  - [Global Illumination](#global-illumination)
  - [Ray Tracing and Path Tracing](#ray-tracing-and-path-tracing)
  - [Volumetric Rendering](#volumetric-rendering)
  - [Textures and Sampling](#textures-and-sampling)
  - [Post-Processing](#post-processing)
  - [Anti-Aliasing and Upscaling](#anti-aliasing-and-upscaling)
  - [Color, Tone Mapping and HDR](#color-tone-mapping-and-hdr)
  - [Natural Phenomena](#natural-phenomena)
  - [Non-Photorealistic Rendering](#non-photorealistic-rendering)
- [Going Further](#going-further)
  - [Physics](#physics)
  - [Machine Learning](#machine-learning)
  - [Research Papers](#research-papers)
  - [Conferences](#conferences)
  - [Blogs](#blogs)
  - [Channels](#channels)
- [Community and Career](#community-and-career)
  - [Communities](#communities)
  - [Looking for Work](#looking-for-work)
  - [Similar Lists](#similar-lists)

## Learning Path
0. [Creative Coding for Beginners](https://thecodingtrain.com/tracks/learning-processing/processing) [video] *(New to programming)*
1. [How to Start C++ Development?](https://github.com/W4RH4WK/cpp-init) [article]
2. [Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra) [video] [article] *(Click on "Read" for exercises)*
3. [3D Math Primer for Graphics and Game Development](https://gamemath.com/) [book]
4. [How do Video Game Graphics Work?](https://www.youtube.com/watch?v=C8YtdC8mxTU) [video]
5. [Ray Tracing in One Weekend](https://raytracing.github.io/) [book]
6. [Tiny Renderer](https://haqr.eu/tinyrenderer/) [article]
7. [Learn OpenGL](https://learnopengl.com/) [book]
8. [The Book of Shaders](https://thebookofshaders.com/) [book]
9. [RenderDoc](https://renderdoc.org/) [tool]
10. [A Trip Through the Graphics Pipeline (2011)](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/) [article]
11. [Vulkan Guide](https://vkguide.dev/) [book] *(or [DirectX 12](#directx-12) / [Metal](#metal) depending on platform)*

## Foundations

### Getting Started
- [Graphics Programming – Where To Start?](https://www.stefanpijnacker.nl/article/graphics-programming-where-to-start/) [article]
- [Getting Started In Computer Graphics](https://www.jeremyong.com/graphics/2024/05/19/getting-started-in-computer-graphics/) [article]
- [How Do I Become a Graphics Programmer?](https://gpuopen.com/learn/how_do_you_become_a_graphics_programmer/) [article]
- [How to Start Learning Computer Graphics Programming](https://erkaman.github.io/posts/beginner_computer_graphics.html) [article]
- [Finding Your Home in Graphics Programming](https://alextardif.com/LearningGraphics.html) [article]
- [Drinking from the Firehose: Learning Computer Graphics Techniques and Programming](https://miketuritzin.com/post/how-to-learn-computer-graphics-techniques-and-programming/) [article]
- [What To Learn To Be A Real Time Graphics Programmer](https://blog.demofox.org/2026/07/01/what-to-learn-to-be-a-graphics-programmer/) [article]
- [Self-Starting As A 3D Graphics Programmer](https://www.youtube.com/watch?v=b4iIg32g65s) [video]
- [How to Start a Career in Computer Graphics Programming](https://www.youtube.com/watch?v=AoTxTz31nXY) [video]
- [Getting the Best Graphics Programming Job in UK](https://www.youtube.com/watch?v=KEDNXFSIE5s) [video]
- [Learning Graphics Programming with C++](https://www.youtube.com/watch?v=vL87j4wup1U) [video]

### C++
- [How to Start C++ Development?](https://github.com/W4RH4WK/cpp-init) [article]
- [Learn C++](https://www.learncpp.com) [book]
- [Hacking C++](https://hackingcpp.com/index.html) [article]
- [C++ By Example](https://cppbyexample.com/) [article]
- [Modern C++ Features](https://github.com/AnthonyCalandra/modern-cpp-features) [article]
- [Game Programming Patterns](https://gameprogrammingpatterns.com/) [book]
- [Data Structures and Algorithms Tutorial](https://www.w3schools.com/dsa/index.php) [article]
- [C++ Programming Exercises](https://www.w3resource.com/cpp-exercises/) [exercises]
- [Project Euler](https://projecteuler.net/about) [exercises]
- [Cpp Quiz](https://cppquiz.org/) [exercises]
- [How do CPUs Work?](https://www.youtube.com/watch?v=16zrEPOsIcI) [video]
- [How does Computer Cache, Memory, and Storage Work?](https://www.youtube.com/watch?v=TfhL5kBiQVI) [video]
- [Data-Oriented Design](https://www.dataorienteddesign.com/dodbook/) [book]
- [Data Oriented Design Resources](https://github.com/dbartolini/data-oriented-design) [list]
- [Bit Twiddling Hacks](https://graphics.stanford.edu/~seander/bithacks.html) [article]
- [C++ Reference](https://en.cppreference.com/w/) [documentation]

### Mathematics

#### Linear Algebra

- [Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra) [article] [video] *(Click on "Read" for exercises)*
- [Vector Math for 3D Computer Graphics](https://chortle.ccsu.edu/VectorLessons/index.html) [article]
- [Immersive Math](https://immersivemath.com/ila/index.html) [book]
- [Linear Algebra Done Right](https://linear.axler.net/) [book]
- [Linear Algebra Done Wrong](https://sites.google.com/a/brown.edu/sergei-treil-homepage/linear-algebra-done-wrong) [book]
- [Geometric Algebra](https://www.youtube.com/playlist?list=PLffJUy1BnWj3deu0cqpk5CiePiwORDiCe) [video]

#### Calculus and Trigonometry

- [Trigonometry](https://www.mecmath.net/trig/) [book]
- [Calculus GREEN Vol 1: Asymptotics](https://www.youtube.com/playlist?list=PL8erL0pXF3JaFSMdokheNMvTa96jdc4GU) [video]
- [Calculus BLUE Vol 1 : Vectors & Matrices](https://www.youtube.com/playlist?list=PL8erL0pXF3JYm7VaTdKDaWc8Q3FuP8Sa7) [video]

#### Math for Graphics and Games

- [3D Math Primer for Graphics and Game Development](https://gamemath.com/) [book]
- [Fundamental Math for Game Developers](https://pikuma.com/blog/math-for-game-developers) [article]
- [Essential Mathematics for Aspiring Game Developers](https://www.youtube.com/watch?v=DPfxjQ6sqrc) [video]
- [Math for Game Developers](https://www.youtube.com/playlist?list=PLW3Zl3wyJwWOpdhYedlD-yCB7WQoHf-My) [video]
- [Math for Game Devs](https://www.youtube.com/playlist?list=PLImQaTpSAdsArRFFj8bIfqMk2X7Vlf3XF) [video]
- [Game Math 101, Writing your Own 2D Math in C++](https://randygaul.github.io/math/2022/09/18/Game-Math-101-Writing-your-Own-2D-Math-in-CPP.html) [article]
- [Coding Math](https://www.youtube.com/playlist?list=PLSjXzDREmGkqJA7rpGxV8xaQ589kHU4rX) [video]
- [Visualizing Quaternions](https://eater.net/quaternions) [video] *(Interactive)*
- [A Primer on Bézier Curves](https://pomax.github.io/bezierinfo/) [article]
- [Nature of Code](https://natureofcode.com/) [book]

#### Reference and Tools

- [3D Math Cheat Sheet](https://antongerdelan.net/teaching/3dprog1/maths_cheat_sheet.pdf) [pdf]
- [Real Time Rendering: Linear Algebra and Trigonometry](https://www.realtimerendering.com/Real-Time_Rendering_4th-Appendices.pdf) [book]
- [Desmos](https://www.desmos.com/) [tool] *(Math tools)*

## Graphics Fundamentals

### Overview
- [How do Video Game Graphics Work?](https://www.youtube.com/watch?v=C8YtdC8mxTU) [video]
- [A Brief History of Graphics](https://www.youtube.com/watch?v=QyjyWUrHsFc) [video]
- [What Makes Computer Generated Images Look Real?](https://www.youtube.com/watch?v=iOlehM5kNSk) [video]
- [Every Graphics API Explained In 11 Minutes](https://www.youtube.com/watch?v=MPIiF5G-f3k) [video]
- [Scratchapixel: Learn Computer Graphics Programming](https://www.scratchapixel.com/) [book]

### Courses
- [Pixar in a Box](https://www.khanacademy.org/computing/pixar) [course]
- [Introduction to Computer Graphics](https://www.youtube.com/playlist?list=PLplnkTzzqsZTfYh4UbhLGpI5kGd5oW_Hh) [course]
- [Interactive Computer Graphics](https://www.youtube.com/playlist?list=PLplnkTzzqsZS3R5DjmCQsqupu43oS9CFN) [course]
- [6.837: Introduction to Computer Graphics](https://www.youtube.com/playlist?list=PLQ3UicqQtfNuBjzJ-KEWmG1yjiRMXYKhh) [course]
- [CMU 15-462/662: Computer Graphics](http://15462.courses.cs.cmu.edu/fall2020/) [course]
- [TU Wien Rendering / Ray Tracing Course](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi) [course]
- [Graphics Codex](https://graphicscodex.com/) [course]
- [Introduction To Modern Rendering](https://alelievr.github.io/Modern-Rendering-Introduction/) [course]

### Software Rendering

#### Rasterization

- [Tiny Renderer](https://haqr.eu/tinyrenderer/) [article]
- [Basic 2D Rasterization](https://magcius.github.io/xplain/article/rast1.html) [article]
- [Rasterization in One Weekend](https://tayfunkayhan.wordpress.com/2018/11/24/rasterization-in-one-weekend/) [article]
- [Implementing A Tiny CPU Rasterizer](https://lisyarus.github.io/blog/posts/implementing-a-tiny-cpu-rasterizer-part-1.html) [article]

#### Ray Tracing

- [Ray Tracing in One Weekend](https://raytracing.github.io/) [book]
- [Computer Graphics from Scratch](https://www.gabrielgambetta.com/computer-graphics-from-scratch/) [book] *(Also covers rasterization)*
- [Build Your Own 3D Renderer](https://avikdas.com/build-your-own-raytracer/) [article]
- [Tiny RayTracer](https://github.com/ssloy/tinyraytracer/wiki) [article]
- [Tiny RayCaster](https://github.com/ssloy/tinyraycaster/wiki) [article]
- [Physically Based Rendering](https://pbr-book.org/) [book]

## GPU Fundamentals

### GPU Architecture
- [How do Graphics Cards Work? Exploring GPU Architecture](https://www.youtube.com/watch?v=h9Z4oGN89MU) [video]
- [A Trip Through the Graphics Pipelines for Young Bloods](https://www.jeremyong.com/cpp/2021/05/20/graphics-pipelines-for-young-bloods/) [article]
- [A Trip Through the Graphics Pipeline (2011)](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/) [article]
- [A Trip Through The Graphics Pipeline (Remastered)](https://alaingalvan.gitbook.io/a-trip-through-the-graphics-pipeline) [article]
- [Introduction to Compute Shaders](https://anteru.net/blog/2018/intro-to-compute-shaders/) [article]
- [GPU Architectures](https://drive.google.com/file/d/12ahbqGXNfY3V-1Gj5cvne2AH4BFWZHGD/view) [slides]

### Shaders
- [The Book of Shaders](https://thebookofshaders.com/) [book]
- [Shadertoy](https://www.shadertoy.com/) [tool]
- [OpenGL 4 Shaders](https://antongerdelan.net/opengl/shaders.html) [article]
- [3D Game Shaders For Beginners](https://lettier.github.io/3d-game-shaders-for-beginners/index.html) [book]
- [A Beginner's Guide to Coding Graphic Shaders](https://code.tutsplus.com/series/a-beginners-guide-to-coding-graphics-shaders--cms-834) [article]
- [Introduction to Shader Art Coding](https://www.youtube.com/watch?v=f4s1h2YETNY) [video]
- [GLSL 2D Tutorials](https://www.shadertoy.com/view/Md23DV) [article]
- [Shader School](https://github.com/stackgl/shader-school) [exercises]
- [Shader Academy](https://shaderacademy.com/) [exercises]
- [Shaders Monthly](https://www.youtube.com/playlist?list=PL8vNj3osX2PzZ-cNSqhA8G6C1-Li5-Ck8) [video]

## Graphics APIs

### OpenGL

#### Tutorials

- [Learn OpenGL](https://learnopengl.com/) [book]
- [OpenGL Tutorials](https://www.opengl-tutorial.org/) [book]
- [Anton's OpenGL 4 Tutorials](https://antongerdelan.net/opengl/) [book] [article]
- [OpenGL Step By Step](https://ogldev.org/) [video]
- [OpenGL Introduction](https://open.gl/introduction) [article]
- [An Intro to Modern OpenGL](https://duriansoftware.com/joe/an-intro-to-modern-opengl.-table-of-contents) [book]
- [MBSoftworks OpenGL Tutorials](https://www.mbsoftworks.sk/tutorials/) [article]
- [A Hitchhiker's Guide to OpenGL](https://github.com/bartvbl/A-Hitchhikers-Guide-to-OpenGL) [book]
- [OpenGL Tutorials (YouTube)](https://www.youtube.com/playlist?list=PLPaoO-vpZnumdcb4tZc4x5Q-v7CkrQ6M-) [video]

#### Going Deeper

- [Best Practices for Modern OpenGL](https://juandiegomontoya.github.io/modern_opengl.html) [article]
- [A Guide to Modern OpenGL Functions](https://github.com/fendevel/Guide-to-Modern-OpenGL-Functions) [article]
- [How to write a renderer for modern graphics APIs](https://blog.mecheye.net/2023/09/how-to-write-a-renderer-for-modern-apis/) [article]
- [OpenGL Is Not Right-Handed](https://www.gingerbill.org/article/2024/11/10/opengl-is-not-right-handed/) [article]

#### Reference

- [Docs GL - OpenGL Documentation](https://docs.gl/) [documentation]
- [OpenGL Hardware Database](https://opengl.gpuinfo.org/) [documentation]

### Vulkan

#### Tutorials

- [Vulkan In 30 Minutes](https://renderdoc.org/vulkan-in-30-minutes.html) [article]
- [How to Vulkan in 2026](https://www.howtovulkan.com/) [article]
- [How to make OpenGL usage Vulkan like](https://developer.nvidia.com/opengl-vulkan) [article]
- [Transitioning from OpenGL to Vulkan](https://developer.nvidia.com/transitioning-opengl-vulkan) [article]
- [Vulkan Guide](https://vkguide.dev/) [book]
- [Khronos Vulkan Tutorial](https://docs.vulkan.org/tutorial/latest/00_Introduction.html) [article]
- [Vulkan Tutorial](https://vulkan-tutorial.com/) [book]
- [API Without Secrets](https://www.intel.com/content/www/us/en/developer/articles/training/api-without-secrets-introduction-to-vulkan-part-1.html) [article]
- [I am Graphics and So Can You](https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1) [article]
- [Learn Vulkan from code samples](https://paminerva.github.io/docs/LearnVulkan/LearnVulkan) [article]
- [Vulkan Lecture Series](https://www.youtube.com/playlist?list=PLmIqTlJ6KsE1Jx5HV4sd2jOe3V1KMHHgn) [video]
- [Vulkan's YouTube Channel](https://www.youtube.com/@Vulkan) [video]

#### Going Deeper

- [Vulkan Synchronization Primer - Part I](https://www.jeremyong.com/vulkan/graphics/rendering/2018/11/22/vulkan-synchronization-primer/) [article]
- [Vulkan Synchronization Primer - Part II](https://www.jeremyong.com/vulkan/graphics/rendering/2018/11/23/vulkan-synchonization-primer-part-ii/) [article]
- [Writing an Efficient Vulkan Renderer](https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/) [article]
- [Tips and Tricks: Vulkan Dos and Don'ts](https://developer.nvidia.com/blog/vulkan-dos-donts/) [article]
- [NVIDIA Vulkan Ray Tracing Tutorial](https://github.com/nvpro-samples/vk_raytracing_tutorial_KHR/) [article]

#### Code Samples
- [Vulkan Examples](https://github.com/SaschaWillems/Vulkan) [source code]
- [Keen Games' Vulkan Backend Snapshot](https://github.com/keengames/vulkan_backend) [source code]

#### Reference
- [Vulkan Spec](https://registry.khronos.org/vulkan/specs/1.1/html/vkspec.html) [documentation]
- [Vulkan Hub](https://vkdoc.net/) [documentation]
- [Vulkan Hardware Database](https://vulkan.gpuinfo.org/) [documentation]

### DirectX 11

#### Tutorials
- [Learn DirectX 11](https://graphicsprogramming.github.io/learnd3d11/) [book]
- [DirectX 11 on Windows 10 Tutorial](https://www.rastertek.com/tutdx11win10.html) [article]
- [DirectX 11 - Braynzar Soft Tutorials](https://www.braynzarsoft.net/viewtutorial/q16390-braynzar-soft-directx-11-tutorials) [article]

#### Code Samples
- [Minimal D3D11, Part I](https://gist.github.com/d7samurai/261c69490cce0620d0bfc93003cd1052) [source code]
- [Minimal D3D11, Part II](https://gist.github.com/d7samurai/aee35fd5d132c51e8b0a78699cbaa1e4) [source code]
- [Minimal D3D11, Part III](https://gist.github.com/d7samurai/abab8a580d0298cb2f34a44eec41d39d) [source code]
- [Minimal D3D11 bonus material: extra minimal triangle](https://gist.github.com/d7samurai/1e9a1f1a366740f7d8a3a20397fcfa6b) [source code]
- [Minimal D3D11 bonus material: pixel art antialiasing](https://gist.github.com/d7samurai/9f17966ba6130a75d1bfb0f1894ed377) [source code]
- [Minimal D3D11 sprite renderer](https://gist.github.com/d7samurai/8f91f0343c411286373161202c199b5c) [source code]
- [Minimal D3D11 sprite renderer NEO](https://gist.github.com/d7samurai/e51adec8a440126d028b87406556079b) [source code]

#### Reference
- [DirectX 11 Documentation](https://learn.microsoft.com/en-us/windows/win32/direct3d11/atoc-dx-graphics-direct3d-11) [documentation]

### DirectX 12

#### Tutorials
- [A Gentle Introduction to DirectX 12](https://alextardif.com/DX12Tutorial.html) [article]
- [Learning DirectX 12](https://www.3dgep.com/learning-directx-12-1/) [article]
- [Learn DirectX 12](https://paminerva.github.io/LearnDirectX/presentation.html#) [book]
- [Learn DirectX from code samples](https://paminerva.github.io/docs/LearnDirectX/LearnDirectX) [article]
- [Compute with DirectX 12](https://github.com/stefanpgd/Compute-DirectX12-Tutorial) [article]

#### Going Deeper
- [Breaking Down Barriers](https://therealmjp.github.io/posts/breaking-down-barriers-part-1-whats-a-barrier/) [article]
- [GPU Memory Pools in D3D12](https://therealmjp.github.io/posts/gpu-memory-pool/) [article]
- [Bindless Rendering in DirectX12 and SM6.6](https://rtarun9.github.io/blogs/bindless_rendering/) [article]
- [Nvidia's API Performance Blog](https://developer.nvidia.com/blog/tag/advanced-api-performance) [article]

#### Code Samples
- [Learn DirectX 12 Samples](https://github.com/PAMinerva/LearnDirectX-samples) [source code]
- [Microsoft's DirectX Samples](https://github.com/microsoft/DirectX-Graphics-Samples) [source code]

#### Reference
- [DirectX 12 Documentation](https://learn.microsoft.com/en-us/windows/win32/direct3d12/direct3d-12-graphics) [documentation]
- [DirectX 12 Spec](https://microsoft.github.io/DirectX-Specs/) [documentation]

### Metal

#### Tutorials
- [Metal Tutorial](https://metaltutorial.com/) [book]
- [30 Days of Metal](https://gist.github.com/ole/a1c95cf6a4ebbef2a7827a911301d503) [article]
- [MacOS Metal with C++](https://www.youtube.com/playlist?list=PLn3eTxaOtL2N8v1zUWS1fxaQVI3L3wG0w) [video]
- [3D Game Engine with C++ and Metal](https://www.youtube.com/playlist?list=PLjgVkKlBynWwRbyQASXbpB1fo8GuWNjYl) [video]
- [Drawing Graphics on Apple Vision with the Metal Rendering API](https://github.com/gnikoloff/drawing-graphics-on-apple-vision-with-metal-rendering-api) [article]

#### Code Samples
- [Metal By Example](https://github.com/metal-by-example) [source code]
- [Metal C++ Examples](https://github.com/MattGuerrette/Metal) [source code]
- [Learning Metal with metal-cpp](https://github.com/LeeTeng2001/metal-cpp-cmake) [source code]

#### Reference
- [Metal Documentation](https://developer.apple.com/metal/) [documentation]
- [Getting Started with Metal-cpp](https://developer.apple.com/metal/cpp/) [documentation]

### WebGL
- [WebGL2 Fundamentals](https://webgl2fundamentals.org/) [book]
- [WebGL Fundamentals](https://webglfundamentals.org/) [book]
- [Learn WebGL](https://learnwebgl.brown37.net/) [book]
- [WebGL Academy](http://www.webglacademy.com/) [course]

### WebGPU
- [WebGPU Fundamentals](https://webgpufundamentals.org/) [book]
- [Your First WebGPU App](https://codelabs.developers.google.com/your-first-webgpu-app) [course]
- [WebGPU Unleashed](https://shi-yan.github.io/webgpuunleashed/) [book]
- [Learn WebGPU for C++](https://eliemichel.github.io/LearnWebGPU/) [book]
- [Learn WebGPU](https://sotrh.github.io/learn-wgpu/) [book] *(Rust)*
- [Compute Toys](https://compute.toys/) [tool] *(Shadertoy for WebGPU shaders)*

### Tooling (Debuggers)
- [RenderDoc](https://renderdoc.org/) [tool]
- [NVIDIA Nsight Graphics](https://developer.nvidia.com/nsight-graphics) [tool]
- [PIX](https://devblogs.microsoft.com/pix/introduction/) [tool]
- [Intel Graphics Performance Analyzers](https://www.intel.com/content/www/us/en/developer/tools/graphics-performance-analyzers/overview.html) [tool]
- [AMD Developer Tools Suite](https://gpuopen.com/tools/) [tool]
- [GPU Reshape](https://github.com/GPUOpen-Tools/GPU-Reshape) [tool]
- [Metal Debugger](https://developer.apple.com/documentation/xcode/metal-debugger) [tool]
- [GPU View](https://graphics.stanford.edu/~mdfisher/GPUView.html) [tool]
- [Tracy](https://github.com/wolfpld/tracy) [tool] *(CPU and GPU profiler)*
- [The RAD Debugger](https://github.com/EpicGamesExt/raddebugger) [tool]

## Rendering Techniques

### Renderer Architecture

- [A Primer On Efficient Rendering Algorithms & Clustered Shading](http://www.aortiz.me/2018/12/21/CG.html) [article] *(Start here — forward, deferred, tiled/Forward+, and clustered in one piece)*
- [Clustered Deferred and Forward Shading](https://www.cse.chalmers.se/~uffe/clustered_shading_preprint.pdf) [pdf] *(Olsson et al., the original clustered shading paper)*
- [Render Graphs and Vulkan — a Deep Dive](https://themaister.net/blog/2017/08/15/render-graphs-and-vulkan-a-deep-dive/) [article]
- [Framegraph, Synchronization, and Lighting](https://vkguide.dev/docs/ascendant/ascendant_light/) [article]
- [GPU Driven Rendering Overview](https://vkguide.dev/docs/gpudriven/gpu_driven_engines/) [article] *(Written for Legacy VkGuide; techniques still apply)*
- [Niagara: Building a Vulkan Renderer From Scratch](https://github.com/zeux/niagara) [source code] [video] *(GPU culling, meshlets, task/mesh shaders, written live on stream)*
- [Visibility Buffer Rendering with Material Graphs](https://filmicworlds.com/blog/visibility-buffer-rendering-with-material-graphs/) [article]
- [My Toy Renderer, Part 3: Rendering Basics](https://momentsingraphics.de/ToyRenderer3RenderingBasics.html) [article] *(Visibility buffer in a hybrid raster/ray-traced renderer)*

### Geometry, Culling and LOD
- [Introduction to Turing Mesh Shaders](https://developer.nvidia.com/blog/introduction-turing-mesh-shaders/) [article] *(Meshlets and the task/mesh pipeline)*
- [Mesh Shading Part 1: Rendering Meshlets](https://chaoticbob.github.io/2024/01/24/mesh-shading-part-1.html) [article] *(D3D12, Metal and Vulkan samples)*
- [Meshlet Size Tradeoffs](https://zeux.io/2023/01/16/meshlet-size-tradeoffs/) [article]
- [meshoptimizer](https://github.com/zeux/meshoptimizer) [source code] *(Meshlet building, simplification, vertex cache optimization)*
- [Hierarchical-Z Map Based Occlusion Culling](https://www.rastergrid.com/blog/2010/10/hierarchical-z-map-based-occlusion-culling/) [article]
- [Two-Pass Hierarchical Z-Buffer Occlusion Culling](https://medium.com/@Lucmomber/two-pass-hierarchical-z-buffer-occlusion-culling-93171c5a9808) [article]
- [A Deep Dive into Nanite Virtualized Geometry](https://advances.realtimerendering.com/s2021/Karis_Nanite_SIGGRAPH_Advances_2021_final.pdf) [slides]
- [A Deep Dive into Nanite Virtualized Geometry](https://www.youtube.com/watch?v=eviSykqSUUw) [video] *(Same talk, presented)*

### Materials and Shading
- [Filament: Physically Based Rendering](https://google.github.io/filament/Filament.md) [book] *(Derives the whole BRDF from first principles, with code)*
- [Physically Based Shading in Theory and Practice](https://blog.selfshadow.com/publications/s2014-shading-course/) [slides] *(Includes Naty Hoffman's "Physics and Math of Shading" — the best short intro to BRDFs)*
- [Moving Frostbite to Physically Based Rendering](https://www.ea.com/frostbite/news/moving-frostbite-to-pb) [slides] [pdf] *(120 pages of production detail: materials, lighting, camera, IBL)*
- [PBR Theory](https://learnopengl.com/PBR/Theory) [article] *(The gentlest starting point, with a working implementation after it)*
- [Physically Based Rendering](https://pbr-book.org/) [book] *(Offline, but the reference for reflection models)*

### Lighting and Shadows
- [Shadow Mapping](https://learnopengl.com/Advanced-Lighting/Shadows/Shadow-Mapping) [article] *(Start here)*
- [Common Techniques to Improve Shadow Depth Maps](https://learn.microsoft.com/en-us/windows/win32/dxtecharts/common-techniques-to-improve-shadow-depth-maps) [article] *(Acne, peter-panning, bias, filtering)*
- [Cascaded Shadow Maps](https://learn.microsoft.com/en-us/windows/win32/dxtecharts/cascaded-shadow-maps) [article]
- [A Sampling of Shadow Techniques](https://therealmjp.github.io/posts/shadow-maps/) [article] *(Cascade fitting, stabilization, PCF, VSM, EVSM, MSM)*
- [MJP's Shadows Sample](https://github.com/TheRealMJP/Shadows) [source code] *(D3D11 companion to the article above)*
- [A Primer On Efficient Rendering Algorithms & Clustered Shading](http://www.aortiz.me/2018/12/21/CG.html) [article] *(Also the best explanation of light culling)*

### Global Illumination
- [Building Real-Time Global Illumination: Part 1](https://jason.today/gi) [article] *(Interactive; raymarching, SDFs, jump flood)*
- [Radiance Cascades: Building Real-Time Global Illumination](https://jason.today/rc) [article] *(Interactive; sequel to the above)*
- [GM Shaders: Radiance Cascades](https://mini.gmshaders.com/p/radiance-cascades) [article] *(Short conceptual overview)*
- [Voxel-Based Global Illumination](https://wickedengine.net/2017/08/voxel-based-global-illumination/) [article] *(Voxel cone tracing, implementation walkthrough)*
- [Dynamic Diffuse Global Illumination with Ray-Traced Irradiance Fields](http://jcgt.org/published/0008/02/01/) [paper] *(DDGI)*
- [Scaling Probe-Based Real-Time Dynamic Global Illumination for Production](https://jcgt.org/published/0010/02/01/) [paper]
- [A Gentle Introduction to ReSTIR](https://intro-to-restir.cwyman.org/) [course] [slides] *(Start with the course notes, not the papers)*
- [Lumen: Real-Time Global Illumination in Unreal Engine 5](https://advances.realtimerendering.com/s2022/index.html) [slides]
- [Radiance Caching and Surfel GI](https://advances.realtimerendering.com/s2021/) [slides] *(Epic's radiance caching and EA SEED's GIBS)*
- [Raytraced Global Illumination Denoising](https://interplayoflight.wordpress.com/2022/03/26/raytraced-global-illumination-denoising/) [article]

### Ray Tracing and Path Tracing
- [Ray Tracing in One Weekend](https://raytracing.github.io/) [book] *(All three volumes; the second and third cover Monte Carlo and importance sampling)*
- [Physically Based Rendering](https://pbr-book.org/) [book] *(The reference for light transport and sampling)*
- [How to Build a BVH](https://jacco.ompf2.com/2022/04/13/how-to-build-a-bvh-part-1-basics/) [article] *(Ten parts: SAH, binned building, refitting, TLAS/BLAS, GPU traversal)*
- [How to Build a BVH — Source Code](https://github.com/jbikker/bvh_article) [source code]
- [Ray Tracing Gems I and II](https://www.realtimerendering.com/raytracinggems/) [book]
- [NVIDIA Vulkan Ray Tracing Tutorial](https://github.com/nvpro-samples/vk_raytracing_tutorial_KHR/) [article] *(Hardware RT, acceleration structures, shader binding tables)*
- [TU Wien Rendering / Ray Tracing Course](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi) [course]

### Volumetric Rendering
- [A Scalable and Production Ready Sky and Atmosphere Rendering Technique](https://sebh.github.io/publications/egsr2020.pdf) [paper] *(The atmosphere model used in Unreal Engine)*
- [Nubis: Authoring Realtime Volumetric Cloudscapes with the Decima Engine](https://advances.realtimerendering.com/s2017/Nubis%20-%20Authoring%20Realtime%20Volumetric%20Cloudscapes%20with%20the%20Decima%20Engine%20-%20Final%20.pdf) [slides]
- [Nubis, Evolved](https://www.guerrilla-games.com/read/nubis-evolved) [slides] *(Flying through clouds, volumetric VFX)*
- [Real-time Volumetrics and VFX](https://www.schneidervfx.com/) [slides] *(Index of every Nubis talk, 2015 to 2023)*
- [Physically Based Sky, Atmosphere and Cloud Rendering](https://www.ea.com/frostbite/news/physically-based-sky-atmosphere-and-cloud-rendering) [slides] *(Frostbite; also covers froxel volumetrics)*
- [Real-Time Samurai Cinema: Lighting, Atmosphere, and Tone Mapping in Ghost of Tsushima](https://advances.realtimerendering.com/s2021/jpatry_advances2021/index.html) [slides] *(Readable HTML; haze, clouds, fog with multiple scattering)*

### Textures and Sampling
- [Understanding BCn Texture Compression Formats](https://www.reedbeta.com/blog/understanding-bcn-texture-compression-formats/) [article]
- [Sharper Mipmapping using Shader Based Supersampling](https://bgolus.medium.com/sharper-mipmapping-using-shader-based-supersampling-ed7aadb47bec) [article]
- [Normal Mapping for a Triplanar Shader](https://bgolus.medium.com/normal-mapping-for-a-triplanar-shader-10bf39dca05a) [article]
- [The Best Darn Grid Shader (Yet)](https://bgolus.medium.com/the-best-darn-grid-shader-yet-727f9278b9d8) [article] *(A deep dive on derivatives, filtering and moiré)*

### Post-Processing
- [Next Generation Post Processing in Call of Duty: Advanced Warfare](https://www.iryoku.com/next-generation-post-processing-in-call-of-duty-advanced-warfare/) [slides] *(Bloom, motion blur, bokeh DOF; the source of the pyramidal bloom everyone uses)*
- [Screen Space Reflections in Killing Floor 2](https://sakibsaikia.github.io/graphics/2016/12/26/Screen-Space-Reflection-in-Killing-Floor-2.html) [article]
- [FidelityFX Stochastic Screen-Space Reflections](https://gpuopen.com/manuals/fidelityfx_sdk/fidelityfx_sdk-page_techniques_stochastic-screen-space-reflections/) [documentation] *(Hi-Z traversal and denoising, with open source)*

### Anti-Aliasing and Upscaling
- [A Survey of Temporal Antialiasing Techniques](http://behindthepixels.io/assets/files/TemporalAA.pdf) [pdf] *(The single best overview of TAA and temporal upsampling)*
- [Temporal Antialiasing Starter Pack](https://alextardif.com/TAA.html) [article] *(Implementation walkthrough with background reading)*
- [A Survey of Temporal Antialiasing Techniques: Presentation Notes](https://interplayoflight.wordpress.com/2020/05/30/a-survey-of-temporal-antialiasing-techniques-presentation-notes/) [article]
- [SMAA: Enhanced Subpixel Morphological Antialiasing](https://www.iryoku.com/smaa/) [article] [source code]
- [Anti-aliased Alpha Test: The Esoteric Alpha To Coverage](https://bgolus.medium.com/anti-aliased-alpha-test-the-esoteric-alpha-to-coverage-8b177335ae4f) [article]
- [AMD FidelityFX Super Resolution 2](https://gpuopen.com/fidelityfx-superresolution-2/) [source code] *(Full source for a shipping temporal upscaler; FSR 4 is signed binaries only)*

### Color, Tone Mapping and HDR
- [Tone Mapping](https://64.github.io/tonemapping/) [article] *(Reinhard through filmic through ACES, with code and comparisons)*
- [Tone Mapping](https://bruop.github.io/tonemapping/) [article] *(Covers auto-exposure and the curves side by side)*
- [Filmic Tonemapping Operators](http://filmicworlds.com/blog/filmic-tonemapping-operators/) [article] *(John Hable's original Uncharted 2 curve)*
- [ACES Filmic Tone Mapping Curve](https://knarkowicz.wordpress.com/2016/01/06/aces-filmic-tone-mapping-curve/) [article] *(The fit everyone ships)*
- [Real-Time Samurai Cinema: Lighting, Atmosphere, and Tone Mapping in Ghost of Tsushima](https://advances.realtimerendering.com/s2021/jpatry_advances2021/index.html) [slides] *(Custom color space for atmospheric lighting, plus tone mapping)*

### Natural Phenomena
- [Simulating Ocean Water](https://graphics.ucsd.edu/courses/rendering/2005/jdewall/tessendorf.pdf) [pdf] *(Tessendorf; the FFT ocean every game uses)*
- [Ocean Rendering with Fast Fourier Transform](https://arm-software.github.io/opengl-es-sdk-for-android/ocean_f_f_t.html) [article] *(Tessendorf implemented in compute shaders)*
- [Insomniac's Water Rendering System](https://www.gamedevs.org/uploads/insomniac-water.pdf) [pdf]
- [Separable Subsurface Scattering](https://www.iryoku.com/separable-sss/) [article] [source code] *(Skin, in under 0.5 ms)*
- [Real-Time Realistic Skin Translucency](https://www.iryoku.com/translucency/) [article]
- [Experimenting with Concurrent Binary Trees for Large-Scale Terrain Rendering](https://advances.realtimerendering.com/s2021/Siggraph21%20Terrain%20Tessellation.pdf) [slides] *(Adaptive terrain tessellation on the GPU)*

### Non-Photorealistic Rendering
- [The Quest for Very Wide Outlines](https://bgolus.medium.com/the-quest-for-very-wide-outlines-ba82ed442cd9) [article] *(Inverted hull, jump flood, and why each one breaks)*
- [Non-photorealistic Rendering](https://www.cs.princeton.edu/courses/archive/fall22/cos426/lectures/Lecture-15.pdf) [slides] *(Princeton COS 426: toon shading, hatching, stylized strokes, paper effects)*
- [Real-Time Rendering Resources: Non-Photorealistic Rendering](https://www.realtimerendering.com/) [list] *(Chapter 15 links)*
- [Acerola](https://www.youtube.com/@Acerola_t) [video] *(Regular stylized and NPR shader breakdowns)*

## Going Further

### Physics
- [Ten Minute Physics](https://matthias-research.github.io/pages/tenMinutePhysics/index.html) [video]
- [Game Physics in One Weekend Series](https://gamephysicsweekend.github.io/) [book]
- [Game Physics](https://gafferongames.com/categories/game-physics/) [article]
- [Physics For Game Dev](https://www.youtube.com/playlist?list=PLA0dXqQjCx0QDKPHhvSXxhV6B-igBNEmx) [video]
- [Erin Catto's Box2D Publications](https://box2d.org/publications/) [article] [video]

### Machine Learning
- [Machine Learning for Game Developers](https://www.youtube.com/watch?v=sTAqWRsEiy0) [video]
  - [Machine Learning for Game Devs: Part 1](https://www.ea.com/seed/news/machine-learning-game-devs-part-1) [article]
  - [Machine Learning for Game Devs: Part 2](https://www.ea.com/seed/news/machine-learning-game-devs-part-2) [article]
  - [Machine Learning for Game Devs: Part 3](https://www.ea.com/seed/news/machine-learning-game-devs-part-3) [article]
- [Crash Course in Deep Learning](https://boksajak.github.io/blog/DeepLearning) [book]
- [Adventures in Neural Rendering](https://interplayoflight.wordpress.com/2026/02/10/adventures-in-neural-rendering/) [article]
- [Game AI Pro](https://www.gameaipro.com/) [book] *(NPC behaviour, not rendering)*

### Research Papers

#### Reading and Writing Papers

- [How to Read Rendering Research Papers](https://morgan3d.github.io/advanced-ray-tracing-course/reading-research.pdf) [pdf]
- [How to Present a Rendering Paper](https://morgan3d.github.io/advanced-ray-tracing-course/present-research.pdf) [pdf]

#### Journals, Proceedings, and Aggregators

- [Ke-Sen Huang's Home Page](https://kesen.realtimerendering.com/)
- [Journal of Computer Graphics Techniques](https://jcgt.org/)
- [High Performance Graphics](https://www.highperformancegraphics.org/)
- [Rendering Engine Architecture](https://enginearchitecture.org/index.htm)

#### Industry Research

- [EA - Rendering and Lighting Research](https://www.ea.com/technology/research/rendering-and-lighting)
- [Guerrilla Games - Publication](https://www.guerrilla-games.com/tags/publication)
- [Activision Research](https://research.activision.com/)
- [Valve Corporation Publications](https://www.valvesoftware.com/en/publications)
- [AMD Publications](https://gpuopen.com/learn/publications/)
- [Nvidia Publications](https://research.nvidia.com/publications)
- [Unity Publications](https://unity.com/publications)
- [Pixar Research](https://graphics.pixar.com/library/)
- [GGX Research](https://ggx-research.github.io/publications.html) *(Grenoble graphics research team)*

#### Academic Labs

- [Keenan Crane](https://www.cs.cmu.edu/~kmcrane/)
- [Realistic Graphics Lab Publications](https://rgl.epfl.ch/publications)
- [KIT Computer Graphics Group](https://cg.ivd.kit.edu/english/publikationen.php)
- [Utah Graphics Lab](https://graphics.cs.utah.edu/research/publications/)
- [U.C. Berkeley Computer Graphics Papers](http://graphics.berkeley.edu/papers/)

### Conferences
- [SIGGRAPH Advances in Real-Time Rendering](https://www.youtube.com/channel/UC9V4KS8ggGQe_Hfeg1OQrWw)
- [High-Performance Graphics](https://www.youtube.com/@HighPerformanceGraphics)
- [Rendering Engine Architecture](https://www.youtube.com/@renderingenginearchitectur3543)
- [Graphics Programming Conference](https://youtube.com/@graphicsprogrammingconference)
- [Digital Dragons](https://www.youtube.com/@DigitalDragonsForGamedev/)
- [Game Developers Conference](https://www.youtube.com/@Gdconf) (you'll have to search for graphics related talks)

### Blogs
- [Graphics Programming Weekly](https://www.jendrikillner.com/tags/weekly/)
- [Real Time Rendering](https://www.realtimerendering.com/blog/)
- [Adrian Courrèges](https://www.adriancourreges.com/blog/)
- [Behind the Pretty Frames](https://mamoniem.com/category/behind-the-pretty-frames/)
- [The Code Corsair](https://www.elopezr.com)
- [Game Art Tricks](https://simonschreibt.de/game-art-tricks/)
- [Bartosz Ciechanowski](https://ciechanow.ski/archives/)
- [Inigo Quilez](https://iquilezles.org/)
- [Blog At The Bottom of The Sea](https://blog.demofox.org/)
- [Eric Arnebäck](https://erkaman.github.io/articles.html)
- [Interplay of Light](https://interplayoflight.wordpress.com/)
- [Alain Galvan](https://alain.xyz/blog)
- [GFX Caffeinist Blog](https://boksajak.github.io/)
- [Self Shadow](https://blog.selfshadow.com/)
- [Wicked Engine](https://wickedengine.net/category/devblog/)
- [Ray Tracey's Blog](https://raytracey.blogspot.com/)
- [Aras Pranckevičius](https://aras-p.info/blog/)
- [Bits, pixels, cycles and more](https://zeux.io/)
- [The Real MJP](https://therealmjp.github.io/posts/)
- [Simon Coenen](https://simoncoenen.com/blog)
- [Clean Rinse](https://blog.mecheye.net/)
- [Maister's Graphics Adventures](https://themaister.net/blog/)
- [Sebastian Aaltonen](https://www.sebastianaaltonen.com/)
- [The ryg blog](https://fgiesen.wordpress.com/)
- [Nathan Reed](https://www.reedbeta.com/)
- [c0de517e](https://www.c0de517e.com/)
- [Bart Wronski](https://bartwronski.com/)
- [Ben Golus](https://bgolus.medium.com/)
- [Jacco Bikker](https://jacco.ompf2.com/)
- [Jorge Jimenez](https://www.iryoku.com/)

### Channels
- [Sebastian Lague](https://www.youtube.com/@SebastianLague)
- [Acerola](https://www.youtube.com/@Acerola_t)
- [SimonDev](https://www.youtube.com/@simondev758)
- [Inigo Quilez](https://www.youtube.com/@InigoQuilez/)
- [Digital Foundry](https://www.youtube.com/user/DigitalFoundry)
- [Kishimisu](https://www.youtube.com/@kishimisu/)

## Community and Career

### Communities
- [Graphics Programming Discord](https://discord.com/invite/m35J6Bk)
- [Vulkan Discord](https://discord.gg/vulkan)
- [Together C & C++ Discord](https://discord.gg/tccpp)
- [Mathematics Discord](https://discord.gg/maths)
- [r/GraphicsProgramming](https://old.reddit.com/r/GraphicsProgramming/)
- [r/MetalProgramming](https://www.reddit.com/r/MetalProgramming/)
- [r/OpenGL](https://www.reddit.com/r/opengl/)
- [r/WebGL](https://www.reddit.com/r/webgl/)
- [r/WebGPU](https://www.reddit.com/r/webgpu/)
- [r/Vulkan](https://www.reddit.com/r/vulkan/)

### Looking for Work

#### Getting Hired

- [If You're Serious About Pursuing a Career in Computer Graphics](https://old.reddit.com/r/gameenginedevs/comments/17nsp1m/how_to_get_into_game_engine_programming/k7v4l91/?context=3) [comment]
- [Advice on Looking for Work from a AAA Game Dev](https://old.reddit.com/r/GraphicsProgramming/comments/1fu8qi4/cant_get_a_job_feeling_very_desperate_and/lpyjmmj/) [comment]
- [Applying for Entry Level Graphic Jobs in Games](https://alextardif.com/GraphicsJobGuide.html) [article]
- [How to Get A Job in Game Design](https://www.youtube.com/playlist?list=PLW3Zl3wyJwWPoqjWDgybGxOAZhdUBAhyR) [video]
- [How to Get into the Game Industry](https://www.youtube.com/watch?v=evhBepR92yw) [video]
- [Game Programmer Resume Tips](https://github.com/unpacklo/game-programmer-resume-tips) [article]

#### Interviewing

- [Junior Graphics Programmer Interview Questions](https://erkaman.github.io/posts/junior_graphics_programmer_interview.html) [article]
- [Interviewing for Junior Programming Positions](https://clementpirelli.wordpress.com/2023/05/31/interviewing-for-junior-programming-positions/) [article]
- [Interviewing Graphics Programmers](https://www.jeremyong.com/graphics/interviewing/2023/08/05/graphics-programmer-interviewing/) [article]
- [Interview Questions](https://aras-p.info/blog/2016/11/05/Interview-questions/) [article]
- [Insider Guide to Tech Interviews](https://bartwronski.com/2022/01/04/insider-guide-to-tech-interviews/) [article]
- [Interviewing for Game Programming](https://lazyfoo.net/articles/article12_interviewing-for-game-programming/index.php) [article]
- [Leetcode for Graphics Interviews?](https://www.reddit.com/r/GraphicsProgramming/comments/ymt0qq/leetcode_for_graphics_interviews/iv60as6/?context=3) [comment]
- [18 Months of Game Programming Interviews](https://www.reddit.com/r/gamedev/comments/9n847g/18_months_of_game_programming_interviews/) [comment]
- [Graphics Interview at Meta Reality Labs](https://www.reddit.com/r/GraphicsProgramming/comments/1arygtk/graphics_interview_at_meta_reality_labs/) [comment]

### Similar Lists
- [Graphics Developer Roadmap](https://github.com/prographon/graphics-developer-roadmap)
- [3D Graphics Programming for Beginners](https://docs.google.com/document/d/1JwwLYxFMDwuxX4Sc3znE-8jVIQMW1LWjuvYeLpiVf_8/edit?tab=t.0)
- [Computer Graphics Resources](https://legends2k.github.io/note/cg_resources/)
- [Learn Game Engine Programming](https://engine-programming.net/)
- [GPU Optimization for GameDev](https://gist.github.com/silvesthu/505cf0cbf284bb4b971f6834b8fec93d)