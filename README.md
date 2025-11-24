```
                                          satrajit@rutgers
        @@@@@@@@@@@@@@@@                  ────────────────────────────────────────────────
      @@@@@@@@@@@@@@@@@@@@                OS: MS ECE (Machine Learning)
    @@@@@@@@@@@@@@@@@@@@@@@@              University: Rutgers University - New Brunswick
   @@@@@@@        @@@@@@@@@@@@            GPA: 4.0 / 4.0
  @@@@@@@          @@@@@@@@@@@            Research: Graphics | GPU | Neural Rendering
  @@@@@@            @@@@@@@@@@            Exchange: Princeton University
  @@@@@@            @@@@@@@@@@            ────────────────────────────────────────────────
  @@@@@@@          @@@@@@@@@@@            
   @@@@@@@        @@@@@@@@@@@@            Languages.Systems: C++20, C, CUDA C++
    @@@@@@@@@@@@@@@@@@@@@@@@              Languages.ML: Python, PyTorch, TensorFlow
      @@@@@@@@@@@@@@@@@@@@                Languages.Web: JavaScript, TypeScript
        @@@@@@@@@@@@@@@@                  Languages.Shading: GLSL, HLSL
           @@@@@@@@                       ────────────────────────────────────────────────
                                          
                                          Graphics.APIs: OpenGL 4.6, Vulkan, CUDA 12.x
                                          Graphics.Techniques: Render Graphs, PBR
                                          Graphics.Research: GPU Scheduling, Interop
                                          ────────────────────────────────────────────────
                                          
                                          ML.Vision: NeRF, 3D Gaussian Splatting
                                          ML.Domains: Scene Reconstruction, Neural Render
                                          ML.Multimodal: Audiovisual Perception
                                          ────────────────────────────────────────────────
                                          
                                          Tools.Build: CMake, Ninja, Git
                                          Tools.Debug: RenderDoc, NVIDIA Nsight
                                          Tools.Systems: Linux, WSL2, Docker
                                          ────────────────────────────────────────────────
```

---

## RESEARCH INTERESTS

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│  Real-Time Rendering Systems                                        │
│  └─ GPU scheduling algorithms and render graph optimization         │
│  └─ Hardware-software co-design for graphics pipelines              │
│  └─ CPU-GPU parallelism and synchronization primitives              │
│                                                                     │
│  Neural Rendering                                                   │
│  └─ Neural radiance fields and 3D Gaussian splatting                │
│  └─ Differentiable rendering and inverse graphics                   │
│  └─ Efficient training for real-time applications                   │
│                                                                     │
│  Computational Photography                                          │
│  └─ Physics-based image relighting and material capture             │
│  └─ Multi-view geometry and camera calibration                      │
│  └─ Structure from motion and dense reconstruction                  │
│                                                                     │
│  Immersive Systems                                                  │
│  └─ VR/AR rendering pipelines and optimization                      │
│  └─ Real-time physics simulation on GPU                             │
│  └─ Human-computer interaction in virtual environments              │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

## CURRENT WORK

### LAGEngine - Graphics Research Testbed

```
┌──────────────────────────────────────────────────────────────────────┐
│ PROJECT    : Custom C++ Game Engine & GPU Scheduling Research        │
│ STATUS     : Active Development                                       │
│ FOCUS      : Performance Measurement & Optimization                   │
├──────────────────────────────────────────────────────────────────────┤
│                                                                       │
│ Architecture                                                          │
│ ├─ DAG-based render graph with explicit pass dependencies            │
│ ├─ Automatic resource lifetime tracking and barrier insertion        │
│ ├─ Multithreaded work-stealing task scheduler                        │
│ └─ Lock-free job queue for CPU-GPU overlap                           │
│                                                                       │
│ GPU Interoperability                                                  │
│ ├─ CUDA-OpenGL zero-copy buffer sharing                              │
│ ├─ Direct GPU buffer writes via mapped memory                        │
│ └─ Synchronized texture updates between compute and graphics         │
│                                                                       │
│ Instrumentation                                                       │
│ ├─ Per-frame timing with CPU and GPU timestamps                      │
│ ├─ Command queue depth and occupancy metrics                         │
│ ├─ Synchronization overhead profiling                                │
│ └─ GPU utilization and memory bandwidth analysis                     │
│                                                                       │
│ Goal: Identify scheduling bottlenecks through empirical measurement  │
│                                                                       │
└──────────────────────────────────────────────────────────────────────┘
```

### Neural Scene Reconstruction - Princeton Research Exchange

```
┌──────────────────────────────────────────────────────────────────────┐
│ PROGRAM    : Princeton University Research Exchange                  │
│ DURATION   : 2024                                                     │
│ FOCUS      : Neural Rendering Techniques                             │
├──────────────────────────────────────────────────────────────────────┤
│                                                                       │
│ Neural Radiance Fields (NeRF)                                         │
│ └─ Volumetric scene representation with neural networks              │
│ └─ Differentiable volume rendering for novel view synthesis          │
│ └─ Training strategies for sparse and dense view scenarios           │
│                                                                       │
│ 3D Gaussian Splatting                                                 │
│ └─ Explicit 3D scene representation with Gaussian primitives         │
│ └─ Real-time rendering through rasterization                         │
│ └─ Optimization for high-quality reconstruction                      │
│                                                                       │
│ Neural Character Generation                                           │
│ └─ Animatable 3D avatar creation from limited data                   │
│ └─ Neural skinning and deformation models                            │
│ └─ Real-time rendering of dynamic human characters                   │
│                                                                       │
└──────────────────────────────────────────────────────────────────────┘
```

---

## TECHNICAL PROJECTS

```
┌────────────────────────────────────────────────────────────────────┐
│                                                                    │
│ VR/AR Systems Portfolio                                            │
│ ├─ VR Fitness Application                                          │
│ │  └─ 3rd Place, Google x GeeksforGeeks "Solving for India"       │
│ ├─ VR Warehouse Training System                                    │
│ │  └─ Interactive learning modules and spatial annotation         │
│ ├─ Architectural Visualization Platform                            │
│ │  └─ Real-time walkthroughs with dynamic lighting               │
│ └─ Virtual Cinema Experience                                       │
│    └─ Social VR environment with synchronized playback            │
│                                                                    │
│ Computer Vision Projects                                           │
│ ├─ Geometry-Guided Image Relighting                               │
│ │  └─ Extended StyLitGAN with physics-based constraints           │
│ ├─ Stereo Reconstruction System                                    │
│ │  └─ Disparity estimation and 3D point cloud generation          │
│ └─ Multi-View Geometry Pipeline                                    │
│    └─ Epipolar geometry and structure from motion                 │
│                                                                    │
│ Software Engineering                                               │
│ ├─ Code & Conquer - Gamified Coding Platform                      │
│ │  └─ Full-stack with Docker execution engine, Stripe payments    │
│ ├─ Quantitative Trading Infrastructure                             │
│ │  └─ Real-time data, backtesting, workflow automation           │
│ └─ Physics Simulation with CUDA                                    │
│    └─ Parallel rigid body dynamics and collision detection        │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
```

---

## EDUCATION

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│ Master of Science in Electrical & Computer Engineering              │
│ Rutgers University - New Brunswick                                  │
│ Expected: May 2025 | GPA: 4.0 / 4.0                                │
│                                                                     │
│ Concentration: Machine Learning                                     │
│                                                                     │
│ Relevant Coursework:                                                │
│ ├─ Machine Vision                                                   │
│ ├─ Software Engineering                                             │
│ ├─ Programming for Finance                                          │
│ ├─ Computer Graphics                                                │
│ ├─ GPU Computing                                                    │
│ └─ Deep Learning                                                    │
│                                                                     │
│ Research Exchange:                                                  │
│ └─ Princeton University - Neural Rendering & 3D Reconstruction      │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

## GITHUB STATISTICS

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=satrajitghosh183&show_icons=true&theme=default&hide_border=true&title_color=000000&icon_color=000000&text_color=000000&bg_color=ffffff" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=satrajitghosh183&theme=default&hide_border=true&background=ffffff&stroke=000000&ring=000000&fire=000000&currStreakLabel=000000" />

<img width="60%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=satrajitghosh183&layout=compact&theme=default&hide_border=true&title_color=000000&text_color=000000&bg_color=ffffff&langs_count=8" />

</div>

---

## RESEARCH PHILOSOPHY

```
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║  "Measure honestly. Build iteratively. Tune based on data."      ║
║                                                                   ║
║  The best research emerges from the careful interplay between    ║
║  theoretical understanding and empirical validation. My approach ║
║  emphasizes rigorous measurement, systematic experimentation,    ║
║  and evidence-based optimization.                                ║
║                                                                   ║
╚═══════════════════════════════════════════════════════════════════╝
```

---

## CONTACT

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│ Email.Personal : sg2231@rutgers.edu                                 │
│ LinkedIn       : linkedin.com/in/satrajit-ghosh                     │
│ GitHub         : github.com/satrajitghosh183                        │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

<div align="center">

```
Last Updated: November 2024
```

[![Profile Views](https://komarev.com/ghpvc/?username=satrajitghosh183&color=black&style=flat-square&label=Profile+Views)](https://github.com/satrajitghosh183)

</div>
