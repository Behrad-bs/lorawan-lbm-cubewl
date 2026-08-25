<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:081410,30:0F3D30,50:1B5240,70:0F3D30,100:081410&height=220&text=LoRaWAN%20LBM%20CubeWL&fontSize=52&fontColor=EDE6D6&fontAlignY=38&desc=Stack%20Integration%20and%20Porting&descAlignY=58&descSize=20&descColor=C97C4B&animation=fadeIn" width="100%" alt="header" />

`PART NO. LORAWAN-LBM-01` &nbsp;·&nbsp; `REV. 2026.08` &nbsp;·&nbsp; `FIRMWARE MODULE`

<br/>

> ⚠️ **IMPORTANT NOTICE:** The source code for this repository is currently restricted. <br/> **You must submit a request to gain access to the repository codes.** See `Section 05` for details.

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=1200&color=D4AF37&center=true&vCenter=true&width=900&height=50&lines=LoRaWAN+Stack+Integration;Semtech+LoRa+Basics+Modem+(LBM);STM32CubeWL+Porting+and+Optimization;Low-Power+Wide-Area+Network+Firmware;Building+Reliable+IoT+Nodes" alt="Typing animation" />

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

<div align="center">

|  |  |  |
|:--:|:--:|:--:|
| `01` General Description | `02` Key Features | `03` Tech Stack & Hardware |
| `04` Architecture Diagram | `05` Code Access Request | `06` Support & Contact |

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

<br/>

## `01` 📋 General Description

This repository contains the implementation, porting, and integration of the **LoRaWAN stack** utilizing the **Semtech LoRa Basics™ Modem (LBM)** tailored for the **STM32CubeWL** microcontroller family. 

Designed for low-power IoT applications, this firmware architecture bridges the gap between Semtech's advanced modem features and STMicroelectronics' robust sub-GHz hardware, providing a stable, production-ready foundation for LoRaWAN end-nodes.

<div align="center">

| Specification | Value |
|:--|:--|
| **Core Technology** | LoRaWAN / LoRa Basics Modem (LBM) |
| **Target Hardware** | STMicroelectronics STM32WL Series |
| **Development Env** | STM32CubeIDE / Makefile / CMake |
| **Optimization** | Ultra-Low Power (ULP) & Memory Constrained |
| **Status** | Active Development / Controlled Access |

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

## `02` ✨ Key Features

- **Seamless LBM Integration:** Full integration of Semtech's LoRa Basics Modem v4.x/v3.x into the STM32CubeWL ecosystem.
- **Hardware Abstraction Layer:** Highly optimized HAL integration for radio control (Sub-GHz PHY).
- **Advanced Low-Power Modes:** Proper handling of STM32WL STOP2 and Standby modes in conjunction with LBM sleep cycles.
- **LoRaWAN Class Support:** Ready for Class A, Class B, and Class C device profiles.
- **Event-Driven Architecture:** Minimal CPU wake-up times utilizing hardware RTC and interrupt lines.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

## `03` ⚙️ Tech Stack & Hardware

<p align="center">
<a href="https://en.cppreference.com/w/c"><img src="https://img.shields.io/badge/C-0F3D30?style=for-the-badge&logo=c&logoColor=EDE6D6" /></a>
<a href="https://www.st.com/en/microcontrollers-microprocessors/stm32wl-series.html"><img src="https://img.shields.io/badge/STM32WL-8B4A2B?style=for-the-badge&logo=stmicroelectronics&logoColor=EDE6D6" /></a>
<a href="https://lora-alliance.org/"><img src="https://img.shields.io/badge/LoRaWAN-0E6E76?style=for-the-badge&logoColor=EDE6D6" /></a>
<a href="https://www.semtech.com/lora"><img src="https://img.shields.io/badge/Semtech%20LBM-0E6E76?style=for-the-badge&logoColor=EDE6D6" /></a>
<a href="https://www.arm.com/"><img src="https://img.shields.io/badge/ARM%20Cortex--M4%2FM0%2B-8B4A2B?style=for-the-badge&logo=arm&logoColor=EDE6D6" /></a>
<a href="https://cmake.org/"><img src="https://img.shields.io/badge/CMake-081410?style=for-the-badge&logo=cmake&logoColor=EDE6D6" /></a>
</p>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

## `04` 🔗 Architecture Diagram

<div align="center">

<img src="assets/block-diagram.svg" width="100%" alt="System Architecture Diagram for STM32CubeWL and LBM" />

<br/>
<sub><i>System Block Diagram outlining the interaction between STM32 HW, Sub-GHz Radio, and LBM Stack.</i></sub>

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

## `05` 🔒 Code Access Request

Due to the nature of this project and potential proprietary integrations, **the source code is not openly available to the public.** 

If you are a researcher, collaborator, or an organization interested in reviewing or using this integration, you must request access.

### 📝 How to request access:
1. Send an email to my contact address provided below.
2. Include `[Code Access Request] LoRaWAN-LBM-CubeWL` in the subject line.
3. Briefly introduce yourself or your organization and the intended use case for this codebase.
4. Provide your GitHub username so I can grant repository permissions upon approval.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:081410,40:0F3D30,50:C97C4B,60:0F3D30,100:081410&height=3" width="420" alt="" />
</div>

## `06` 📦 Support & Contact Information

<div align="center">

<a href="https://www.linkedin.com/in/behrad-kabiri-777138361">
  <img src="https://img.shields.io/badge/LinkedIn-8A6D1E?style=for-the-badge&logo=linkedin&logoColor=EDE6D6" alt="LinkedIn" />
</a>
<a href="mailto:behradkabiri13841384@gmail.com">
  <img src="https://img.shields.io/badge/Email-8A6D1E?style=for-the-badge&logo=gmail&logoColor=EDE6D6" alt="Email" />
</a>
<a href="https://github.com/Behrad-bs">
  <img src="https://img.shields.io/badge/GitHub-8A6D1E?style=for-the-badge&logo=github&logoColor=EDE6D6" alt="GitHub" />
</a>

</div>

<br/>

<div align="center">
  <i>Engineered for Reliability. Built for IoT. 📡</i>
  <br/>
  <sub><i>Part of the Behrad-bs Embedded Ecosystem.</i></sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:081410,30:0F3D30,50:1B5240,70:0F3D30,100:081410&height=110" width="100%" alt="footer" />
