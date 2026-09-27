<!-- ============================== HEADER ============================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Phan%20Van%20Hoang%20Anh&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Autonomous%20Systems%20%E2%80%A2%20Embedded%20AI%20%E2%80%A2%20Real-time%20Control&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="header"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&width=640&lines=Perception+%E2%86%92+Fusion+%E2%86%92+Planning+%E2%86%92+Control;Deploying+AI+on+NVIDIA+Jetson+with+TensorRT;Bare-metal+firmware+on+STM32+%2F+ESP32;Building+autonomous+vehicles+on+real+hardware" alt="typing"/>
</a>

<p>
  <a href="mailto:hoanganh2282003@gmail.com"><img src="https://img.shields.io/badge/Email-hoanganh2282003%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.facebook.com/phan.hoanganh.562/"><img src="https://img.shields.io/badge/Facebook-Phan%20Hoang%20Anh-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Facebook"/></a>
  <a href="https://github.com/hoanganhidi0822"><img src="https://img.shields.io/github/followers/hoanganhidi0822?label=Followers&style=flat-square&logo=github&color=181717" alt="GitHub followers"/></a>
  <img src="https://komarev.com/ghpvc/?username=hoanganhidi0822&style=flat-square&color=2c5364&label=Profile+views" alt="Profile views"/>
</p>

</div>

---

## `$ whoami`

I'm a **Control & Automation Engineering** student building autonomous systems that run on **real hardware**, not just in simulation. My work spans the full robotics stack — from **multi-sensor fusion** and **edge AI perception** to **motion control** and **embedded firmware** — on platforms like **NVIDIA Jetson** and **STM32**.

I care about systems that are *practical, deployable and real-time*: models that are quantized and optimized for the edge, firmware that is deterministic, and pipelines that survive outdoor conditions.

```cpp
struct Engineer {
    const char* name     = "Phan Van Hoang Anh";
    const char* major    = "Control & Automation Engineering";
    const char* focus[4] = { "Autonomous Driving", "Embedded AI",
                             "Sensor Fusion",      "Real-time Control" };
    const char* hardware[4] = { "Jetson AGX Orin", "Jetson Orin Nano",
                                "STM32",           "ESP32" };
    const char* motto    = "If it doesn't run on hardware, it isn't done.";
};
```

---

## 🧭 Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

#### 🚗 Autonomous Driving
End-to-end autonomy pipelines: perception, localization, lane-following and steering control on a real outdoor vehicle.

#### 👁️ Edge AI Perception
Detection, segmentation and monocular depth (**YOLO**, **SegFormer**, **Depth Anything V2**) optimized with **TensorRT** for Jetson.

</td>
<td width="50%" valign="top">

#### 🛰️ Multi-Sensor Fusion
Fusing **GPS RTK**, **IMU** and **camera** data for robust outdoor localization and navigation.

#### ⚙️ Embedded & Real-time Control
Deterministic firmware on **STM32 / ESP32**, glitch-free PWM, motor control and bus communication (**CAN, UART, SPI, I²C**).

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=c,cpp,python,bash&theme=dark" alt="languages"/>

**AI · Perception**

<img src="https://skillicons.dev/icons?i=pytorch,opencv&theme=dark" alt="ai"/>
<br/>
<img src="https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="TensorRT"/>
<img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black" alt="YOLO"/>
<img src="https://img.shields.io/badge/SegFormer-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="SegFormer"/>
<img src="https://img.shields.io/badge/Depth_Anything_V2-4B32C3?style=for-the-badge&logoColor=white" alt="Depth Anything V2"/>

**Robotics · Platforms**

<img src="https://skillicons.dev/icons?i=linux,ubuntu,ros,raspberrypi&theme=dark" alt="platforms"/>
<br/>
<img src="https://img.shields.io/badge/Jetson_AGX_Orin-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="Jetson AGX Orin"/>
<img src="https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="Jetson Orin Nano"/>
<img src="https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS 2"/>

**Embedded**

<img src="https://skillicons.dev/icons?i=arduino&theme=dark" alt="embedded"/>
<br/>
<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" alt="STM32"/>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32"/>
<img src="https://img.shields.io/badge/CAN_·_UART_·_SPI_·_I²C-444444?style=for-the-badge&logoColor=white" alt="Protocols"/>

**Tooling**

<img src="https://skillicons.dev/icons?i=git,github,cmake,vscode&theme=dark" alt="tools"/>

</div>

---

## 🚀 Featured Work

### 🏌️ Autonomous Golf Cart Platform
> Outdoor autonomous navigation deployed on a **real electric golf cart**.

| Layer | What it does | Stack |
|---|---|---|
| **Perception** | Object detection, drivable-area segmentation, monocular depth | YOLO · SegFormer · Depth Anything V2 · TensorRT |
| **Localization** | Centimeter-level global positioning + orientation | GPS RTK · IMU |
| **Planning** | Waypoint navigation and lane-following | Python · C++ · ROS 2 |
| **Control** | Steering and speed actuation on the vehicle | STM32 · CAN / UART |
| **Compute** | On-board real-time inference | Jetson AGX Orin |

```mermaid
flowchart LR
    subgraph Sensors
        CAM[📷 Camera]
        GPS[🛰️ GPS RTK]
        IMU[🧭 IMU]
    end

    subgraph Jetson["NVIDIA Jetson · TensorRT"]
        DET[YOLO<br/>Detection]
        SEG[SegFormer<br/>Segmentation]
        DEP[Depth Anything V2<br/>Depth]
        LOC[Sensor Fusion<br/>Localization]
        PLN[Planner<br/>Waypoints · Lane-following]
    end

    subgraph MCU["STM32 · Real-time"]
        CTL[Steering / Speed<br/>Controller]
    end

    CAM --> DET & SEG & DEP
    GPS --> LOC
    IMU --> LOC
    DET & SEG & DEP --> PLN
    LOC --> PLN
    PLN -- CAN / UART --> CTL
    CTL --> ACT[🚗 Actuators]
```

### ⚡ Embedded Motor Control
> Real-time motor handling on **STM32** for robotics applications.

- Glitch-free PWM generation with safe duty-cycle updates
- Deterministic, interrupt-driven control loops
- Communication with high-level compute over serial / CAN

---

## 📊 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=hoanganhidi0822&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=tokyonight&bg_color=0d1117" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hoanganhidi0822&layout=compact&langs_count=8&hide_border=true&theme=tokyonight&bg_color=0d1117" alt="Top languages"/>

<img width="80%" src="https://streak-stats.demolab.com?user=hoanganhidi0822&hide_border=true&theme=tokyonight&background=0d1117" alt="GitHub streak"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=hoanganhidi0822&hide_border=true&theme=tokyo-night&bg_color=0d1117&area=true" alt="Contribution graph"/>

</div>

---

## 🎯 Currently

- 🔭 Improving robustness of outdoor perception and localization on the golf cart platform
- ⚡ Squeezing more FPS out of Jetson with TensorRT (FP16 / INT8) optimization
- 🌱 Going deeper into state estimation, control theory and ROS 2
- 🤝 Open to collaboration on **autonomous vehicles, robotics and edge AI** projects

---

<div align="center">

**Let's build something that moves.** 🤖

<a href="mailto:hoanganh2282003@gmail.com"><img src="https://img.shields.io/badge/Contact_me-hoanganh2282003%40gmail.com-0f2027?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt="footer"/>

</div>
