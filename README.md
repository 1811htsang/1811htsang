# Hi there, I'm Huynh Thanh Sang (Shang Huang) 👋

### 🚀 Embedded Software / Firmware Engineer
**"I don't just write code; I design a complete embedded product with a full process from schematic design and PCB to software architecture development."**

---

### 🧐 About Me
I am currently a Computer Engineering student at **VNUHCM-UIT** (GPA: **8.55/10**). My passion is mastering the entire process and complex engineering steps to perfect products and solve real-world problems.

- 🔭 **Current Focus:** Developing bare-metal drivers for STM32, multi-core RTOS systems on ESP32; Designing custom schematics & PCBs for STM32 & ESP32 projects.
- 🌱 **Core Philosophy:** Deep understanding of core process & underlaying logic designs.
- 🗣️ **Languages:** Vietnamese (Native), English (C1 - Proficient).

---

### 🛠️ Tech Stack & Arsenal
| Core | Hardware | Protocols | Tools |
| :--- | :--- | :--- | :--- |
| ![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Bash](https://img.shields.io/badge/bash-%234EAA25.svg?style=flat&logo=gnu-bash&logoColor=white) | ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white) | ![Protocols](https://img.shields.io/badge/UART_I2C_SPI-black?style=flat) | ![FreeRTOS](https://img.shields.io/badge/FreeRTOS-green?style=flat) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) |

---

### 🔥 Featured Projects (Under Development)

#### 1. [Field-Serviceable Smart Power Monitor (STM32)](https://github.com/1811htsang/Field-Serviceable-Smart-Power-Monitor-using-STM32F103C8T6.git)
> *Challenges: Bare-metal Optimization (64KB Flash), Class 0.5S Accuracy (IEC 62053-22), 3-Phase Industrial Simulation, Fail-safe Robustness.*
* **Architected** a professional-grade firmware using a **Bare-metal approach** to maximize performance within a constrained **64KB Flash/20KB RAM** footprint, avoiding the overhead of HAL libraries.
* **Developed** a dual-update strategy: A custom bootloader supporting **XMODEM-CRC** via UART for remote servicing and a **microSD-based** recovery mechanism for offline field maintenance.
* **Engineered** a high-reliability system with a multi-layered safety net: **IWDG (LSI-based)** for hardware hangs, **WWDG** for software logic faults, and **CSS (Clock Security System)** to monitor HSE oscillator stability.
* **Implemented** precise energy metering logic using **ADE7758**, achieving **Class 0.5S** accuracy for parameters including Vrms, Irms, Active/Reactive Power, and Power Factor across 3 phases.
* **Designed** a Hardware-in-the-Loop (HIL) testbench using **MCP4728 (DAC)** and **TDA2030 amplifiers** to simulate industrial 3-phase signals from a single-phase source, enabling comprehensive validation without high-voltage risks.
* **Integrated** advanced security and power features: Using **Backup Registers** for state preservation during resets, **RTC Timestamping** for data logging, and **MPU/TAMPER** for system integrity.

#### 2. [Predictive Maintenance via Acoustic Fingerprint (ESP32-S3)](https://github.com/1811htsang/Predictive-Maintenance-via-Acoustic-Fingerprint-on-ESP32-S3.git)
> *Challenges: 96kHz/24-bit High-Fidelity Sampling, Multi-layer Software Architecture, Power Management, Real-time Feature Extraction (MFCC), High-Noise Environment (80dB).*
* **Architected** a modular firmware using **ESP-IDF** with a 3-layer stack: **MCAL** (Hardware Abstraction), **Middleware** (DSP/Feature Extraction), and **Application** (Logic & Predictive Models).
* **Implemented** a high-speed data acquisition pipeline using **I2S** to offload the CPU, achieving a stable **96kHz sampling rate** for precise acoustic fingerprinting.
* **Designed** a precision **Clock Tree** utilizing an external **24.576MHz crystal** and **74HCU04** IC to provide a clean master clock for the **PCM1808 ADC**, ensuring low-jitter audio capture.
* **Developed** a robust hardware front-end incorporating **TL072 Op-amps**, **MAX9812**, **PJ-313B**, **TCT40-16R**, and **PCM1808** to process differential signals from industrial bearings (2000 RPM reference).
* **Engineered** power-efficient routines for battery operation (8-hour minimum) with integrated charging management and state-of-charge (SoC) monitoring.

#### 3. [OTA Software Update Solution with DFU and P2P Scenario Design for End Users](https://github.com/1811htsang/OTA-Software-Update-Solution-with-DFU-and-P2P-Scenario-Design-for-End-Users.git)
> *Challenges: Peer-to-Peer (P2P) firmware distribution, Flash Memory Management, Bandwidth Optimization for IoT.*

* **Developed** a comprehensive **Over-The-Air** (OTA) update system utilizing **Device Firmware Update** (DFU) protocols to enable seamless wireless software enhancements.

* **Design** a specialized **Peer-to-Peer** (P2P) update scenario where updated devices act as local sources to distribute 1MB firmware packages to neighboring targets, significantly reducing cloud bandwidth reliance.

* **Optimized** memory architecture for embedded targets, incorporating a **Safe Rollback mechanism** to restore the previous stable version in case of update failure or system instability.

* **Designed** a user-centric management workflow, bridging the gap between **Servers**, **Gateways**, and **end-user IoT devices** through standardized communication.

---

### 📫 Connect with me
<p align="left">
<a href="https://tinyurl.com/htsang1811-linkedin" target="blank"><img align="center" src="https://img.shields.io/badge/-Shang_Huang-blue?style=flat-square&logo=Linkedin&logoColor=white&link=LINK_LINKEDIN_CUA_BAN" alt="Huynh Thanh Sang" height="28" width="130" /></a>
<a href="mailto:23521341@gm.uit.edu.vn" target="blank"><img align="center" src="https://img.shields.io/badge/Email-Contact_Me-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:23521341@gm.uit.edu.vn" alt="Email" height="28" width="120" /></a>
</p>
