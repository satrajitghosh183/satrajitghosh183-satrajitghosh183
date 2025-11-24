Here’s a full GitHub profile README you can drop into `README.md` in your `satrajitghosh183/satrajitghosh183` repo. It’s set up to work nicely with **lowlighter/metrics** and follows the structure/style ideas from that Medium article.

Adjust anything you don’t like, but this is a solid “professional profile resume” starting point.

---

````md
<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Satrajit%20Ghosh&animation=fadeIn&type=waving&color=gradient&height=120&fontAlignY=35&desc=Graphics%20%7C%20GPU%20Scheduling%20%7C%20VR%20Systems&descAlignY=60" alt="Header" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/satrajit-ghosh/">
    <img src="https://img.shields.io/badge/LinkedIn-Satrajit%20Ghosh-blue?logo=linkedin" />
  </a>
  <a href="mailto:sg2231@rutgers.edu">
    <img src="https://img.shields.io/badge/Email-Contact%20me-red?logo=gmail" />
  </a>
  <!-- Uncomment and update when your portfolio is public
  <a href="https://your-portfolio-url.com">
    <img src="https://img.shields.io/badge/Portfolio-Website-black?logo=firefoxbrowser" />
  </a>
  -->
</p>

---

### 👋 About me

```yaml
name: "Satrajit Ghosh"
role: "MS ECE (Machine Learning) @ Rutgers University – New Brunswick"
gpa: "4.0 / 4.0"
interests:
  - real-time rendering & GPU scheduling
  - game engines & physics simulation
  - VR/AR training and immersive experiences
  - neural rendering & 3D vision
currently:
  - building: "LAGEngine (C++/OpenGL/CUDA engine + research testbed)"
  - exploring:
      - DAG-based render graphs
      - work-stealing schedulers
      - CUDA–OpenGL interop for real-time graphics
values:
  - "measure first, optimize second"
  - "systems that ship and can be profiled"
````

I’m a game developer and software engineer focused on **real-time graphics**, **GPU task scheduling**, and **VR/AR systems**.
Right now, most of my work happens inside **LAGEngine**, my custom C++/OpenGL/CUDA engine that doubles as a research platform for **multithreaded DAG scheduling**, **CUDA stream management**, and **GPU utilization**.

---

### 🛠 Tech stack

**Languages & core**

`C++` · `C` · `Python` · `JavaScript/TypeScript` · `CUDA` · `Bash`

**Graphics, XR & engines**

`OpenGL` · `GLSL` · `CUDA–OpenGL interop` · custom **render graphs** · physics / game engine patterns · `Unity` (for earlier VR work)

**ML / 3D vision**

`PyTorch` · `NeRF` · `Gaussian Splatting` · neural scene reconstruction · multimodal models (audio–visual, e.g. McGurk effect experiments)

**Tools & platforms**

`Git` · `CMake` · `Linux` · `Windows` · GitHub Actions · `Docker` (when needed for tooling and CI)

---

### 🎮 What I build

#### 🔹 LAGEngine – C++/OpenGL/CUDA engine + research testbed

* Custom **2D/3D game and physics engine** used as my master’s thesis platform.
* Implements a **DAG-aware render graph** with explicit render passes and resources.
* Uses **multithreaded scheduling** with work stealing and **CUDA–OpenGL interoperability** so GPU kernels can write directly into graphics buffers and textures.
* Instrumented for **frame timings, queue depths, synchronization and GPU utilization**, so I can actually measure the effect of scheduling policies instead of guessing.

> Repo: `LAGEngine` (C++ · OpenGL · CUDA · Graphics · AI-assisted scheduling)

#### 🔹 VR / AR systems

* **VR fitness/exercise game**
  Built a VR exercise game that won **3rd place** in the *Google & GeeksforGeeks “Solving for India”* competition – focused on **gamified workouts** with deep learning–based tracking.
* **VR warehouse training**
  Recreated an industrial warehouse in VR with **annotation and learning modules** for step-by-step training, built for a real corporate environment (e.g., Ericsson-style warehouse training).
* **VR house tours for architecture**
  Virtual tours for an architecture company so clients can “walk through” spaces before construction.
* **VR movie theatre experiences**
  VR environments and mini-games for entertainment during and after lockdown.
* This line of work led to **a VR-related publication** and multiple **hackathon wins** around immersive training and interaction.

#### 🔹 Neural rendering & 3D vision (Princeton exchange)

Through a competitive exchange program at **Princeton University**, I worked on:

* **Neural Radiance Fields (NeRF)** – building photorealistic 3D scenes from multi-view images with volumetric rendering.
* **Gaussian Splatting** – experimenting with **real-time** point-based rendering for dynamic scenes.
* **Neural scene reconstruction & neural character generation** – pipelines for **animatable 3D avatars** from unstructured images, combining neural rendering and 3D reconstruction techniques.

#### 🔹 Quant-ish and tooling projects

When I’m not inside a graphics pipeline, I like building **tools around quantitative finance and automation**:

* small engines for **signal generation and backtesting**
* automation around **trading workflows** and **data analysis**
* practical scripts for personal finance and scenario modeling

---

### 📊 GitHub metrics (auto-updated)

> These cards are generated using **lowlighter/metrics** via GitHub Actions.([GitHub][1])
> Once you configure the action to output `github-metrics.svg`, this will render automatically.

<p align="center">
  <img src="https://github.com/satrajitghosh183/satrajitghosh183/blob/main/github-metrics.svg" alt="GitHub Metrics" />
</p>

<!--
You can add more variants (calendar, languages, activity, etc.) by generating additional SVGs with different plugin configurations.

Example extra cards (uncomment after you generate them):

<p align="center">
  <img src="https://github.com/satrajitghosh183/satrajitghosh183/blob/main/github-metrics.isocalendar.svg" alt="Isometric commit calendar" />
</p>

<p align="center">
  <img src="https://github.com/satrajitghosh183/satrajitghosh183/blob/main/github-metrics.languages.svg" alt="Languages activity" />
</p>
-->

---

### 🚀 Selected projects

> Pin these repos on your GitHub profile so they show up together with this README.

* **LAGEngine** – C++/OpenGL/CUDA game & physics engine with **DAG scheduling**, **work stealing**, and **CUDA–OpenGL interop** for real-time experiments.
* **VR training + VR fitness** – suite of VR applications for **warehouse training**, **gamified exercise**, **house tours**, and **movie theatre experiences**, including a **Google “Solving for India”** prize-winning project and a **VR-focused publication**.
* **Neural Character Generation** – end-to-end pipeline for turning unstructured 2D images into **realistic, animatable 3D characters** using neural rendering and 3D reconstruction.
* **Multimodal perception (McGurk experiments)** – testing how **deep models handle conflicting audio–visual speech cues**, with custom experimental pipelines and visualizations.
* **Quant & tooling projects** – internal tools for **backtesting**, **signal analysis**, and **workflow automation** in quantitative finance contexts.

---

### 📫 Get in touch

* 💼 LinkedIn: [Satrajit Ghosh](https://www.linkedin.com/in/satrajit-ghosh/)
* ✉️ Email: [sg2231@rutgers.edu](mailto:sg2231@rutgers.edu)

I’m always open to conversations about **graphics/engines**, **GPU scheduling**, **VR/AR**, and **ML-heavy interactive systems**.

````

---

### (Optional) GitHub Actions workflow for Metrics

If you haven’t wired up **lowlighter/metrics** yet, here’s a minimal workflow you can drop into `.github/workflows/metrics.yml` to generate `github-metrics.svg` for your profile repo:​:contentReference[oaicite:1]{index=1}

```yaml
name: GitHub Metrics

on:
  schedule:
    - cron: "0 */24 * * *"    # update once a day
  workflow_dispatch:

jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - name: Generate Metrics
        uses: lowlighter/metrics@latest
        with:
          # REQUIRED: your GitHub token with repo + read:user + read:org scopes
          token: ${{ secrets.METRICS_TOKEN }}

          # Basic setup
          user: satrajitghosh183
          template: classic
          base: header, activity, community, repositories
          config_timezone: America/New_York

          # Some nice plugins (tweak as you like)
          plugins: >
            isocalendar,
            languages,
            lines,
            achievements

          # Plugin configs (examples)
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year
          plugin_languages: yes
          plugin_languages_details: percentage
          plugin_languages_limit: 8
          plugin_lines: yes
          plugin_achievements: yes
          plugin_achievements_threshold: B
          plugin_achievements_secrets: yes

          # Output file
          filename: github-metrics.svg
````



[1]: https://github.com/lowlighter/metrics "GitHub - lowlighter/metrics:  An infographics generator with 30+ plugins and 300+ options to display stats about your GitHub account and render them as SVG, Markdown, PDF or JSON!"
