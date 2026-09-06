<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:1D4ED8,100:06B6D4&height=220&section=header&text=YuHeng%20%7C%20Walker152&fontSize=48&fontColor=F8FAFC&animation=fadeIn&fontAlignY=34&desc=Embodied%20Intelligence%20%C3%97%20Robot%20Navigation&descAlignY=55&descSize=19" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=23&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=760&lines=Making+robots+see%2C+think%2C+and+move.;VLN+%C2%B7+VLA+%C2%B7+WAM+%C2%B7+Embodied+AI;Navigation+%C2%B7+Planning+%C2%B7+Control+%C2%B7+Sim-to-Real;From+language+%26+pixels+to+real-world+robot+motion." alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Beijing%20Institute%20of%20Technology-BIT-0F766E?style=for-the-badge" />
<img src="https://img.shields.io/badge/Focus-Embodied%20Intelligence-2563EB?style=for-the-badge" />
<img src="https://img.shields.io/badge/Robot-Navigation-0891B2?style=for-the-badge" />

</div>

---

## 🤖 About Me

Hi, I'm **YuHeng** 👋

I'm at **Beijing Institute of Technology**, interested in building embodied agents that can **perceive the world, understand instructions, predict what comes next, and move robustly in the physical world**.

My current interests lie around the intersection of:

**Vision-Language Navigation · Vision-Language-Action · World Action Models · Embodied AI · Robot Navigation**

I especially enjoy connecting **learning-based policies** with **classical robotics** — mapping, trajectory optimization, planning and control — and eventually making the whole system run on a real robot.

> **My favorite problem:**
> How do we turn pixels + language + world knowledge into **safe, smooth and intelligent robot motion**?

---

## 🧠 Research Interests

<div align="center">

<img src="https://img.shields.io/badge/VLN-Vision--Language%20Navigation-2563EB?style=flat-square" />
<img src="https://img.shields.io/badge/VLA-Vision--Language--Action-7C3AED?style=flat-square" />
<img src="https://img.shields.io/badge/WAM-World%20Action%20Model-9333EA?style=flat-square" />
<img src="https://img.shields.io/badge/Embodied-AI-0891B2?style=flat-square" />
<img src="https://img.shields.io/badge/Navigation-Robotics-059669?style=flat-square" />
<img src="https://img.shields.io/badge/Sim--to--Real-Robotics-EA580C?style=flat-square" />

</div>

```text
                  ┌───────────────────────┐
                  │   Vision + Language   │
                  └───────────┬───────────┘
                              │
                  ┌───────────▼───────────┐
                  │  VLN · VLA · WAM     │
                  │  World Understanding  │
                  └───────────┬───────────┘
                              │
               ┌──────────────▼──────────────┐
               │  Navigation / Robot Policy │
               └──────────┬───────┬─────────┘
                          │       │
                 Learning │       │ Optimization
                          │       │
                 ┌────────▼──┐ ┌──▼────────────┐
                 │ Diffusion │ │ MINCO · SFC   │
                 │ Policies  │ │ MPC · Search  │
                 └────────┬──┘ └──┬────────────┘
                          │       │
                          └───┬───┘
                              │
                   ┌──────────▼──────────┐
                   │ ROS 2 · Real Robot │
                   └─────────────────────┘
```

---

## 🛰️ What I'm Building

### 🧭 BIT RoboMaster Sentry Navigation

<a href="https://github.com/Walker152/navi_minco_bit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Walker152&repo=navi_minco_bit&theme=github_dark&hide_border=true&bg_color=00000000" />
</a>

A complete ROS 2 autonomous navigation stack for a RoboMaster sentry robot.

```text
Dual Livox MID-360
        ↓
    Point-LIO
        ↓
      ROGMap
        ↓
 Search / MINCO
        ↓
    SE(2) MPC
        ↓
  Behavior Tree
        ↓
    Real Robot
```

**Topics I care about here:** LiDAR perception, LIO, mapping, ESDF, trajectory optimization, MPC, navigation safety and real-time robotics.

---

### 🧠 NavDP × MINCO

<a href="https://github.com/Walker152/NavDP-MINCO">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Walker152&repo=NavDP-MINCO&theme=github_dark&hide_border=true&bg_color=00000000" />
</a>

Exploring how **learning-based navigation policies** can work together with **optimization-based trajectory generation**.

```text
RGB-D Observation
       ↓
Navigation Diffusion Policy
       ↓
 Learned Trajectory / Guide
       ↓
    MINCO + SFC
       ↓
 Dynamically Feasible Motion
```

Experiments around **Isaac Sim / Isaac Lab**, mapless navigation, diffusion policy and constrained trajectory optimization.

---

### 🏟️ Navigation Simulation

<a href="https://github.com/Walker152/nav-simulation">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Walker152&repo=nav-simulation&theme=github_dark&hide_border=true&bg_color=00000000" />
</a>

A Gazebo-based platform for testing the navigation stack before going onto the real robot.

**Gazebo Fortress · ROS 2 · Simulated MID-360 · Point-LIO · GICP · ROGMap · MINCO · MPC**

---

## 🛠️ Robotics Toolbox

### Languages & Core

<p>
<img src="https://skillicons.dev/icons?i=cpp,python,cmake,bash,linux,git&theme=dark" />
</p>

### Robotics & Simulation

<p>
<img src="https://img.shields.io/badge/ROS%202-Humble-22314E?style=for-the-badge&logo=ros&logoColor=white" />
<img src="https://img.shields.io/badge/Nav2-Navigation-2563EB?style=for-the-badge" />
<img src="https://img.shields.io/badge/Gazebo-Fortress-F58113?style=for-the-badge&logo=gazebo&logoColor=white" />
<img src="https://img.shields.io/badge/NVIDIA-Isaac%20Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/Isaac-Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
</p>

### Perception · Mapping · Planning · Control

<p>
<img src="https://img.shields.io/badge/Point--LIO-LiDAR%20Odometry-0EA5E9?style=flat-square" />
<img src="https://img.shields.io/badge/ROGMap-Mapping-0284C7?style=flat-square" />
<img src="https://img.shields.io/badge/PCL-Point%20Clouds-0369A1?style=flat-square" />
<img src="https://img.shields.io/badge/Eigen-Linear%20Algebra-2563EB?style=flat-square" />
<img src="https://img.shields.io/badge/MINCO-Trajectory%20Optimization-7C3AED?style=flat-square" />
<img src="https://img.shields.io/badge/MPC-Control-9333EA?style=flat-square" />
<img src="https://img.shields.io/badge/BehaviorTree.CPP-Decision-DB2777?style=flat-square" />
</p>

---

## 📊 GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Walker152&show_icons=true&theme=github_dark&hide_border=true&bg_color=00000000&rank_icon=github&include_all_commits=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Walker152&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000&langs_count=8" />

</div>

<div align="center">

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Walker152&theme=github-compact&hide_border=true&area=true" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/Walker152/Walker152/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/Walker152/Walker152/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution snake"
    src="https://raw.githubusercontent.com/Walker152/Walker152/output/github-contribution-grid-snake.svg"
  />
</picture>

</div>

---

<div align="center">

### 🌌 Perception → Understanding → Planning → Action

*Trying to make robots a little more intelligent every day.*

<img src="https://komarev.com/ghpvc/?username=Walker152&label=PROFILE+VIEWS&color=0891b2&style=flat-square" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,55:1D4ED8,100:0F172A&height=120&section=footer" />
