<div align="center">

# Gonzalo Olguín Moncada

<a href="https://gonzal0lguin.github.io">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=3B82F6&center=true&vCenter=true&width=620&lines=Robotics+R%26D+Engineer+%40+AMTC;Autonomous+navigation+%C2%B7+Perception+%C2%B7+RL;Generative+planners+meet+vision-language+models;Off+the+keyboard%3A+somewhere+in+the+Andes+%F0%9F%8F%94%EF%B8%8F" alt="Typing intro" />
</a>

<p>
  <a href="https://gonzal0lguin.github.io"><img src="https://img.shields.io/badge/Website-gonzal0lguin.github.io-0F172A?style=for-the-badge&logo=astro&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/gonzalo-olguin"><img src="https://img.shields.io/badge/LinkedIn-gonzalo--olguin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://arxiv.org/abs/2602.01429"><img src="https://img.shields.io/badge/arXiv-2602.01429-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv" /></a>
  <a href="https://gonzal0lguin.github.io/assets/pdf/cv.pdf"><img src="https://img.shields.io/badge/CV-PDF-10B981?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV" /></a>
</p>

</div>

---

## 👋 About me

I'm an **Electrical Engineer** with a **Master of Engineering Sciences** from **Universidad de Chile** (both with highest distinction), working on robots that find their own way through the real, messy outdoors.

- 🤖 **R&D Engineer** at the [Advanced Mining Technology Center (AMTC)](https://www.amtc.cl/): autonomous navigation, perception and hydraulic manipulation for mining and research platforms.
- 🧪 **Lab Manager** of the Robotics Lab, Electrical Engineering Dept., Universidad de Chile.
- 📄 First author of **Sem-NaVAE**, published in **IEEE Robotics and Automation Letters (RA-L), 2026**.
- 🇩🇪 Exchange semester at **TU Munich**: RL for humanoid robot soccer on a NAO.
- 🏔️ When I'm not debugging TF trees, I'm climbing mountains in the Andes. I also build [map tools](https://gonzal0lguin.github.io/en/ascents/route-tool) for them.

---

## 🔬 Research highlight

<table>
<tr>
<td width="42%">
  <a href="https://arxiv.org/abs/2602.01429">
    <img src="https://raw.githubusercontent.com/gonzal0lguin/gonzal0lguin.github.io/main/public/assets/img/posts/sem-navae/hero.png" alt="Sem-NaVAE" />
  </a>
</td>
<td>

**Sem-NaVAE: Semantically-Guided Outdoor Mapless Navigation via Generative Trajectory Priors**<br/>
<sub>G. Olguín, J. Ruiz-del-Solar · <i>IEEE RA-L</i>, vol. 11, no. 8, 2026</sub>

A mapless outdoor planner that splits *where the robot can go* from *where it should go*:

- a **CVAE** with a multi-choice Log-Mean-Exp objective generates **200+ feasible trajectories** per step,
- a lightweight **VLM (CLIPSeg)** scores them from natural-language prompts,
- a local planner executes them, all **in real time and without a map**.

[📄 arXiv](https://arxiv.org/abs/2602.01429) · [🎥 Full run video](https://youtu.be/i3R5ey5O2yk) · [📝 Write-up](https://gonzal0lguin.github.io/projects/sem-navae/)

</td>
</tr>
</table>

---

## 🛠️ Selected projects

<table>
<tr>
<td width="50%" valign="top">
  <a href="https://github.com/gonzal0lguin/monocular-2d-mapping">
    <img src="https://raw.githubusercontent.com/gonzal0lguin/gonzal0lguin.github.io/main/public/assets/img/headers/2dmapping.png" alt="Monocular 2D semantic mapping" />
  </a>
  <h3><a href="https://github.com/gonzal0lguin/monocular-2d-mapping">Monocular 2D Semantic Mapping</a></h3>
  Occupancy and semantic maps from a single RGB camera: segmentation, bird's-eye-view transform and odometry-based fusion on a Husarion Panther in ROS / Gazebo.
  <br/><br/>
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
</td>
<td width="50%" valign="top">
  <a href="https://github.com/gonzal0lguin/path-sampling">
    <img src="https://raw.githubusercontent.com/gonzal0lguin/gonzal0lguin.github.io/main/public/assets/img/headers/path-sampling.png" alt="Curvature-based path sampling" />
  </a>
  <h3><a href="https://github.com/gonzal0lguin/path-sampling">Curvature-Based Path Sampling</a></h3>
  Extracts the most informative waypoints from a global plan (curvature and gradient peaks plus uniform sampling) to feed an RL local planner. Built at AMTC.
  <br/><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" />
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <a href="https://gonzal0lguin.github.io/en/projects/mirar-como-un-robot/">
    <img src="https://raw.githubusercontent.com/gonzal0lguin/gonzal0lguin.github.io/main/public/assets/img/headers/mirar-como-robot.jpg" alt="Looking at a mountain like a robot" />
  </a>
  <h3><a href="https://gonzal0lguin.github.io/en/projects/mirar-como-un-robot/">Looking at a Mountain Like a Robot</a></h3>
  A 160 km "simulated LiDAR" over the Copernicus GLO-30 elevation model: 7,200 rays and about 38 M samples per summit to compute what's visible from each peak.
  <br/><br/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white" /> <img src="https://img.shields.io/badge/GIS-2E7D32?style=flat-square" />
</td>
<td width="50%" valign="top">
  <a href="https://github.com/gonzal0lguin/gonzoBot">
    <img src="https://raw.githubusercontent.com/gonzal0lguin/gonzal0lguin.github.io/main/public/assets/img/headers/gonzo-bot.png" alt="GonzoBot" />
  </a>
  <h3><a href="https://github.com/gonzal0lguin/gonzoBot">GonzoBot</a></h3>
  An open-source, 3D-printed differential-drive robot: custom hardware and electronics, running ROS from the ground up.
  <br/><br/>
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/Fusion_360-F58220?style=flat-square&logo=autodesk&logoColor=white" />
</td>
</tr>
</table>

<details>
<summary><b>More things I've built</b></summary>
<br/>

| Project | What it is |
|---|---|
| [🗺️ Route analyzer](https://gonzal0lguin.github.io/en/ascents/route-tool) | In-browser GPX tool: merge tracks, elevation profile, 3D view, climb splits and a time planner. |
| [ScaraBot](https://github.com/gonzal0lguin/ScaraBot) | 2-DoF SCARA arm that beats you at Tic-Tac-Toe with minimax. |
| [mobb-python](https://github.com/gonzal0lguin/mobb-python) | Minimum Oriented Bounding Box algorithm, used to split occupancy maps optimally. |
| [Jaime-arm](https://github.com/gonzal0lguin/Jaime-arm) | Control for the robotic "neck" of the lab's robot Jaime. |
| [CM25-2430-Driver](https://github.com/gonzal0lguin/CM25-2430-Driver) | Arduino driver for low-cost CM25-2430 brushless DC motors. |
| [gonzal0lguin.github.io](https://github.com/gonzal0lguin/gonzal0lguin.github.io) | My bilingual portfolio and mountaineering log, built with Astro and Tailwind, plus a custom content editor. |

</details>

---

## 💼 Experience

| Role | Where | When |
|---|---|---|
| **R&D Engineer** | Advanced Mining Technology Center (AMTC) | 2026 – present |
| **Lab Manager** | Robotics Lab, Universidad de Chile | 2024 – present |
| **Autonomous Navigation Team Lead** | Bender (RoboCup@Home), Universidad de Chile | 2023 – 2025 |
| **Engineering Intern** | AMTC | 2024 |
| **Robotics Software Engineer** | Maquintel Robotic Services | 2023 |
| **Teaching Assistant** | Universidad de Chile (Mobile Robotics, Duckietown, Comp. Intelligence…) | 2020 – 2025 |

<sub>At Maquintel I worked on 3D mapping of tunnels: ICP/RANSAC point-cloud alignment, IMU sensor fusion for robust odometry, and a Gazebo simulation of the Vizca D400 inspection robot built from scratch.</sub>

---

## 🧰 Toolbox

**Languages & ML**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/JAX-A8B9CC?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" />

**Robotics & Systems**<br/>
<img src="https://img.shields.io/badge/ROS%20%2F%20ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white" />
<img src="https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/MuJoCo-1F6FEB?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />

**Hardware**<br/>
<img src="https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" />
<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" />
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
<img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white" />
<img src="https://img.shields.io/badge/Fusion%20360-F58220?style=for-the-badge&logo=autodesk&logoColor=white" />

**Platforms I've worked with:** Unitree Go2 · Husarion Panther · Clearpath Husky · Pioneer 3DX/3AT · TurtleBot2 · NAO<br/>
**Sensors:** 2D/3D LiDAR · mono/stereo cameras · IMU · RTK-GPS

---

<div align="center">

### 🏔️ Off the keyboard

I log my climbs, routes and summit panoramas, and run a native-plant reforestation project, over at
**[gonzal0lguin.github.io](https://gonzal0lguin.github.io/en/ascents/)**.

<sub>🇨🇱 Spanish (native) · 🇬🇧 English (C1) · 🇩🇪 German (A1) · Based in Santiago, Chile</sub>

<br/><br/>

<a href="mailto:golguinm@gmail.com"><img src="https://img.shields.io/badge/Get%20in%20touch-golguinm%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>
