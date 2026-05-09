# Hi there, I'm Huynh Thanh Sang (Shang Huang) 👋

### 🚀 Embedded Software / Firmware Engineer
**"I specialize in Hardware-Software Co-design, architecting reliable systems from custom event-driven kernels to high-speed mixed-signal PCB layouts."**

---

### 🧐 About Me
I am a 3rd-year Computer Engineering student at **VNUHCM-UIT** (GPA: **8.55/10**). Guided by **First Principles Thinking**, I am passionate about bypassing abstraction layers to master the underlying logic of embedded systems. My goal is to build robust, industrial-grade products by integrating deep firmware optimization with professional hardware engineering.

- 🔭 **Current Focus:** Developing a core-independent event-driven kernel (CIEDPC) and high-fidelity data acquisition systems.
- 🌱 **Core Philosophy:** True system control comes from understanding the synergy between bit-level code and electron-level signals.
- 🗣️ **Languages:** Vietnamese (Native), English (**IELTS 7.0** - Proficient).

---

### 🛠️ Tech Stack & Arsenal
| Core | Hardware & PCB | Peripherals | Tools & Quality |
| :--- | :--- | :--- | :--- |
| ![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Bash](https://img.shields.io/badge/bash-%234EAA25.svg?style=flat&logo=gnu-bash&logoColor=white) | ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white) ![KiCad](https://img.shields.io/badge/KiCad-314E2A?style=flat&logo=kicad&logoColor=white) | ![Protocols](https://img.shields.io/badge/I2S_I2C_SPI_UART_RCC_MQTT_INTR_GPIO-black?style=flat) | ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white) ![Valgrind](https://img.shields.io/badge/Valgrind-5F3F3F?style=flat) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) |

---

### 🔥 Featured Projects

#### 1. [CIEDPC – Custom Independent Event-Driven Programming Core](https://github.com/1811htsang/CIEDPC-Custom-Independent-Event-Driven-Programming-Core.git)
> *Challenges: Core Portability (STM32/ESP32/Linux), Lock-free Communication, O(1) Scheduling, Memory Safety.*
* **Designed** a core-independent framework from the simplified EPCB-vn AKEDP core, enabling 100% functional portability between STM32 for application usages and Linux for testing purposes.
* **Implemented** deterministic Static Memory Pools to minimize RAM fragmentation with Automatic Hardware Scaling, Direct/Indirect Data-to-Message passing and a Signal Injection Bridge for safe ISR-to-Task communication.
* **Developed** an O(1) Table-driven Transition State Machine with built-in Entry/Exit actions, reducing event-dispatching latency to a minimal number of CPU cycles.
* **Leveraged** self-written unit tests and POSIX simulation to validate memory safety and hidden logic errors before real hardware deployment.

#### 2. [Field-Serviceable Smart Power Monitor (STM32)](https://github.com/1811htsang/Field-Serviceable-Smart-Power-Monitor-using-STM32F103C8T6)
> *Challenges: Register-level Optimization, Class 0.5s Accuracy, HIL Testing, High-EMI Industrial Robustness.*
* **Implemented** a Self-Healing Clock Tree with CSS to ensure 24/7 operation in high-EMI industrial environments.
* **Developed** register-level drivers for reliable SPI communication (Ping-Pong logic & Core Systick interference) compatible with Class 0.5s accuracy for the ADE7758 IC.
* **Planned** rigorous verification using SIL (Software-In-the-Loop) and developed a custom HIL Test-Jig using MCP4728 IC to simulate 3-phase power faults.

#### 3. [Predictive Maintenance via Acoustic Fingerprint (ESP32-S3)](https://github.com/1811htsang/Predictive-Maintenance-via-Acoustic-Fingerprint-on-ESP32-S3.git)
> *Challenges: 96ksps/24-bit Signal Integrity, Mixed-Signal PCB Design, Low-jitter Clock Trees.*
* **Architected** a 24-bit/96ksps sampling engine using an external PCM1808 ADC and a custom Pierce Oscillator (74HCU04 IC) for jitter-free synchronization.
* **Designed** a dual-stage analog front-end using TL072IDT Op-Amps with 1MΩ & 2.2KΩ high-impedance inputs for TCT40-16R ultrasonic sensors (20kHz-45kHz), 10KΩ & 1KΩ high-impedance inputs for the MAX9812 amplified microphone module.
* **Integrated** a smart mechanical MUX to switch between MAX9812 & TCT40-16R sensors and PJ-342S 3.5mm audio jack for external computer connections.
* **Implemented** a split ground plane with local bridge to remove crosstalk noise from the Wi-Fi module to the Analog area, ensuring 24-bit signal integrity.

---

### 📫 Connect with me
<p align="left">
<a href="https://tinyurl.com/htsang1811-linkedin" target="blank"><img align="center" src="https://img.shields.io/badge/-Shang_Huang-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Huynh Thanh Sang" height="28" /></a>
<a href="mailto:htsang181105work@gmail.com" target="blank"><img align="center" src="https://img.shields.io/badge/Email-Contact_Me-c14438?style=flat-square&logo=Gmail&logoColor=white" alt="Email" height="28" /></a>
</p>
