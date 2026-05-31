# 🎮 GPU & Graphics Mastery

<p align="center">
  <b>Master GPU Architecture, Graphics APIs, Compute Programming, and Real-Time Rendering</b><br>
  A complete roadmap from GPU hardware fundamentals to Vulkan, CUDA, OpenCL, ray tracing, profiling, and modern graphics engines.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-GPU_Architecture-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Level-Beginner_to_Expert-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Graphics_&_Compute-blue?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/Srivathsan98/GPU-Graphics-Mastery?style=for-the-badge" />
</p>

---

## 🎯 About

**GPU & Graphics Mastery** is a structured roadmap designed to help you:

✔ Understand modern GPU hardware architecture

✔ Learn graphics rendering pipelines

✔ Master OpenGL and OpenGL ES

✔ Learn Vulkan from fundamentals to advanced rendering

✔ Understand GLSL and HLSL shader programming

✔ Learn OpenCL and heterogeneous compute

✔ Master CUDA programming

✔ Build high-performance graphics and compute applications

✔ Understand ray tracing and modern rendering techniques

✔ Profile and optimize GPU workloads

---

## 🗺️ Roadmap Overview

```mermaid
flowchart LR

A[GPU Architecture]
--> B[OpenGL]

B --> C[GLSL]

C --> D[Rendering Fundamentals]

D --> E[OpenGL ES]

E --> F[Advanced Rendering]

F --> G[Window Systems]

G --> H[Vulkan]

H --> I[Vulkan Memory]

I --> J[Vulkan Sync]

J --> K[Vulkan Compute]

K --> L[OpenCL]

L --> M[HLSL]

M --> N[DirectX12]

N --> O[CUDA]

O --> P[CUDA Optimization]

P --> Q[Ray Tracing]

Q --> R[Profiling]

R --> S[Graphics Engines]

S --> T[GPU Driver Internals]

T --> U[GPU Security]

U --> V[Modern GPU Design]
```

---

## 🌐 GitHub Pages

Link to GitHub Page:

https://srivathsan98.github.io/GPU-Graphics-Mastery/GPU-Mastery-Tracker.html

---

## 📚 Learning Modules

### 🏗️ GPU Architecture Fundamentals

* SIMT vs SIMD
* SM / Compute Units
* Warps & Wavefronts
* Register Files
* Shared Memory
* L1/L2 Cache
* Tensor Cores
* RT Cores
* Occupancy
* Memory Hierarchy

### 🟩 OpenGL Core Profile

* VAO
* VBO
* EBO
* Shaders
* Uniforms
* Textures
* Framebuffers
* Blending
* Depth Testing
* Instancing

### 🔷 GLSL Shader Programming

* Vertex Shaders
* Fragment Shaders
* Geometry Shaders
* Tessellation
* Compute Shaders
* PBR
* Shadow Mapping
* Post Processing

### 🎨 OpenGL Advanced Techniques

* DSA
* Bindless Textures
* Persistent Mapping
* Multi Draw Indirect
* Sparse Textures
* GPU Driven Rendering
* Mesh Shaders

### 🌍 3D Math & Rendering Fundamentals

* Vectors
* Matrices
* Quaternions
* MVP Transformations
* Projection
* Frustum Culling
* Ray Casting
* BVH
* Scene Graphs

### 📱 OpenGL ES & Embedded GPUs

* EGL
* GBM
* DRM/KMS
* Mali
* Adreno
* PowerVR
* Tile-Based Rendering
* ASTC
* ETC2

### 🎯 Rendering Techniques

* Deferred Shading
* Forward+
* PBR
* TAA
* SSAO
* HBAO+
* Motion Blur
* DoF
* Volumetric Lighting
* Global Illumination

### 🖱️ Window System Integration

* GLFW
* SDL2
* Wayland
* X11
* DRM/KMS
* Swapchains
* HDR
* Display Pipelines

---

## 🔺 Vulkan Track

### Vulkan Core

* Instance
* Physical Device
* Logical Device
* Queues
* Surface
* Swapchain
* Validation Layers

### Vulkan Pipeline

* Render Passes
* Graphics Pipelines
* Descriptor Sets
* Push Constants
* SPIR-V
* Pipeline Cache

### Vulkan Memory

* Buffers
* Images
* VMA
* Memory Heaps
* Staging Buffers
* Suballocation

### Vulkan Synchronization

* Fences
* Semaphores
* Events
* Pipeline Barriers
* Timeline Semaphores
* Queue Ownership

### Vulkan Compute

* Compute Pipelines
* SSBO
* Dispatch
* Subgroups
* Async Compute

### Vulkan Ray Tracing

* BLAS
* TLAS
* SBT
* Raygen
* Closest Hit
* Any Hit
* Miss Shaders

---

## ⚡ OpenCL Track

* Platform Model
* Devices
* Contexts
* Command Queues
* Buffers
* Images
* NDRange
* Workgroups
* Local Memory
* Profiling
* OpenGL Interop
* SPIR-V

---

## 🪟 DirectX & HLSL

### HLSL

* Shader Semantics
* Constant Buffers
* SRV
* UAV
* CBV

### DirectX 12

* Device
* Command Queue
* Command Lists
* Descriptor Heaps
* Root Signatures
* Resource Barriers

---

## 🚀 CUDA Programming

### CUDA Fundamentals

* CUDA Runtime
* Grid
* Block
* Thread
* Occupancy
* Streams

### CUDA Memory

* Global Memory
* Shared Memory
* Constant Memory
* Unified Memory
* Pinned Memory

### CUDA Optimization

* Coalesced Access
* Warp Efficiency
* Tensor Cores
* Cooperative Groups
* CUDA Graphs

### CUDA Libraries

* cuBLAS
* cuDNN
* TensorRT
* NCCL
* Thrust

---

## 🌈 Ray Tracing

* BVH
* Acceleration Structures
* RTX
* Path Tracing
* Hybrid Rendering
* Denoising
* GI
* Reflections
* Shadows

---

## 📊 GPU Profiling & Optimization

* NVIDIA Nsight
* Nsight Compute
* Nsight Systems
* RenderDoc
* PIX
* Radeon GPU Profiler
* Intel GPA

### Optimization Areas

* Occupancy
* Warp Efficiency
* Memory Bandwidth
* Cache Utilization
* Synchronization
* Pipeline Bubbles

---

## 🧩 Graphics Engines

### Unreal Engine

* Rendering Architecture
* Nanite
* Lumen
* RHI

### Unity

* SRP
* HDRP
* URP

### Custom Engines

* ECS
* Resource Systems
* Render Graphs
* Frame Graphs

---

## ⚙️ GPU Driver & OS Internals

* Mesa
* DRM
* KMS
* Gallium
* Vulkan Drivers
* OpenGL Drivers
* Shader Compilation
* Kernel Interfaces

---

## 🔒 GPU Security

* GPU Isolation
* DMA
* Memory Protection
* Secure Contexts
* Side Channels

---

## 🤖 AI Accelerators & Modern GPUs

* Tensor Cores
* NPUs
* AI Accelerators
* Multi-GPU
* NVLink
* MIG
* Heterogeneous Computing

---

## 🛠️ Hands-On Projects

| Project | Level | Description |
|----------|----------|-------------|
| 🎨 OpenGL Renderer | Beginner | Modern OpenGL rendering engine |
| 🔷 Shader Sandbox | Beginner | GLSL experimentation environment |
| 📱 Embedded Renderer | Intermediate | EGL + GLES rendering |
| 🔺 Vulkan Renderer | Intermediate | Vulkan rendering engine |
| ⚡ OpenCL Image Processor | Intermediate | GPU image processing pipeline |
| 🚀 CUDA Matrix Library | Intermediate | High-performance CUDA kernels |
| 🌈 Ray Tracer | Advanced | CPU/GPU hybrid path tracer |
| 🎯 Deferred Renderer | Advanced | Full deferred rendering pipeline |
| 📊 GPU Profiler Dashboard | Advanced | Nsight/RenderDoc analysis tools |
| 🏗️ Graphics Engine | Expert | Complete custom rendering engine |

---

## 📁 Project Structure

```bash
gpu-graphics-mastery/
│
├── 01-gpu-architecture/
├── 02-opengl-core/
├── 03-glsl/
├── 04-opengl-advanced/
├── 05-rendering-math/
├── 06-opengl-es/
├── 07-rendering-techniques/
├── 08-window-systems/
├── 09-vulkan-core/
├── 10-vulkan-pipeline/
├── 11-vulkan-memory/
├── 12-vulkan-sync/
├── 13-vulkan-compute/
├── 14-opencl/
├── 15-hlsl/
├── 16-directx12/
├── 17-cuda-fundamentals/
├── 18-cuda-memory/
├── 19-cuda-optimization/
├── 20-cuda-libraries/
├── 21-ray-tracing/
├── 22-gpu-profiling/
├── 23-graphics-engines/
├── 24-driver-internals/
├── 25-gpu-security/
├── 26-ai-accelerators/
├── 27-multi-gpu/
├── 28-research-topics/
├── 29-system-design/
├── 30-capstone-project/
└── README.md
```

---

## 🧰 Recommended Tools

| Tool | Purpose |
|--------|---------|
| RenderDoc | Frame Capture & Debugging |
| NVIDIA Nsight Graphics | Graphics Profiling |
| NVIDIA Nsight Compute | CUDA Profiling |
| Nsight Systems | System-wide Analysis |
| PIX | DirectX Profiling |
| Radeon GPU Profiler | AMD Profiling |
| Intel GPA | Intel GPU Analysis |
| Vulkan SDK | Vulkan Development |
| CUDA Toolkit | CUDA Development |
| OpenCL SDK | OpenCL Development |

---

## 🎯 Goals

* 🎮 Understand modern GPU architecture
* 🟩 Master OpenGL & OpenGL ES
* 🔺 Become proficient in Vulkan
* ⚡ Learn OpenCL & CUDA
* 🌈 Understand ray tracing pipelines
* 📊 Profile and optimize GPU workloads
* 🏗️ Build custom rendering engines
* 🤖 Understand AI accelerator hardware

---

## 📈 Progress Tracker

* [ ] GPU Architecture
* [ ] OpenGL
* [ ] GLSL
* [ ] OpenGL Advanced
* [ ] Rendering Fundamentals
* [ ] OpenGL ES
* [ ] Rendering Techniques
* [ ] Window Systems
* [ ] Vulkan Core
* [ ] Vulkan Pipeline
* [ ] Vulkan Memory
* [ ] Vulkan Synchronization
* [ ] Vulkan Compute
* [ ] OpenCL
* [ ] HLSL
* [ ] DirectX 12
* [ ] CUDA Fundamentals
* [ ] CUDA Memory
* [ ] CUDA Optimization
* [ ] CUDA Libraries
* [ ] Ray Tracing
* [ ] GPU Profiling
* [ ] Graphics Engines
* [ ] Driver Internals
* [ ] GPU Security
* [ ] AI Accelerators
* [ ] Multi-GPU
* [ ] Research Topics
* [ ] System Design
* [ ] Capstone Project

---

## 🏆 End Goal

By the end of this roadmap, you should be able to:

✅ Write modern OpenGL applications

✅ Build Vulkan renderers

✅ Develop CUDA and OpenCL compute applications

✅ Design real-time rendering pipelines

✅ Implement ray tracing systems

✅ Profile and optimize GPU workloads

✅ Understand GPU hardware deeply

✅ Build production-grade graphics engines

---

## 📜 Sources

* RTR4 (Real-Time Rendering 4th Edition)
* Vulkan Specification
* OpenGL SuperBible
* GPU Gems
* The Book of Shaders
* NVIDIA CUDA Documentation
* Khronos Documentation

---

<p align="center">
Built with 🎮 + ⚡ + 🔺 + 🌈 + curiosity
</p>