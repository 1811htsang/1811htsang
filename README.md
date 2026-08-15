# Hi there, I'm Huynh Thanh Sang (Shang Huang)

## Embedded System Architect & Operating System Researcher
**"Architecting reliable, deterministic infrastructures for the next generation of event-driven embedded systems."**

## 💡 Professional Philosophy
I am a 3rd-year Computer Engineering student at **VNUHCM-UIT** (GPA: **8.55/10**) with a deep passion for **System Design Thinking**. I don't just write firmware; I build the ecosystems that firmware lives in. My approach combines the rigor of industrial safety standards (ISO 26262/MISRA-C) with the agility of modern DevOps tools (Docker, Kconfig, Jinja2).

- **Current Mission:** Evolving **μEDP** (Event-Driven Framework) into **μE-OS** (Event-Driven OS) — a full-scale embedded OS with high-level features inspired by the Linux Kernel.
- **Strategic Focus:** Unidirectional data flow, infrastructure-as-code for embedded, and automated reliability verification.
- **Languages:** Vietnamese (Native), English (**IELTS 7.0** - Proficient).

## 🛠 Strategic Tech Stack
| System Design & OS | Hardware & Protocols | Infrastructure & Automation | Validation & Quality |
| :--- | :--- | :--- | :--- |
| **Active Object Model**, HSMC (TSM/FSM), Scheduling Theory, Memory Pooling | STM32 (M3/M4/M7), ESP32-S3 (AMP), I2S/I2C/SPI, UART, DMA | **Kconfig**, Jinja2, **Docker Compose**, Python-based Generators | **PLTF/TLC (Pytest)**, Doxygen, Static Analysis, FCR (Fatal Control) |

---

## 🏗 Key Project: The μE-Ecosystem
### [μEDP: micro Event-Driven Programming Framework](https://github.com/1811htsang/uEDP)
> *A high-performance, single-stack RTC framework designed for Zero-Touch Porting and Hard Real-Time determinism.*

*   **Architecture & Design:** Engineered a strict 3-layer decoupled architecture (App-Core-PAL). Implemented **Unidirectional Configuration Pipelines** (`Kconfig` -> `UST` -> `PLD`) to ensure 100% architectural integrity.
*   **Memory & Data Guard:** Designed **Deterministic Memory Pooling (DMP)** and **Global Data Area (GDA)** with **Zero-Copy Reference Passing (D2MP)**. This eliminates memory fragmentation and triệt tiêu "exposed traces" in application logic.
*   **Execution Excellence:** Optimized an **O(1) Bitmask Scheduler** with **Atomic Priority Escalation (APE)** and **Safe LIFO-nested FIFO (S-LnF)**, ensuring microsecond response times for critical events under heavy loads.
*   **Background Services:** Developed **Out-Context Execution (OCE)** with a modifiable execution chain (**mexecjn**), allowing non-critical system services (log dumping, cleanup) to run without jittering the main logic.

### [PLTF & TLC: Portable Local Test Framework](https://github.com/1811htsang/uEDP)
> *A comprehensive Model-Based Testing framework for μE-OS validation.*

*   **Logic Specification:** Created **μE-LS (Logical Syntax-izer)**, a YAML-based DSL for describing complex state machines and system behaviors.
*   **Automated VnV:** Built a **Docker-Compose** driven pipeline that automatically generates C-code handlers from YAML logic and triggers **Hardware-in-the-Loop (HIL)** testing.
*   **Test Level Coverager (TLC):** Implemented automated coverage tracking across **UT (Unit)**, **CT (Component)**, **ST (System)**, and **IT (Integration)** levels, ensuring defect detection on both single-core (STM32) and multi-core (ESP32-S3 AMP) platforms.

---

## 📈 Roadmap to μE-OS (Pre-v1.2.0 & Beyond)
- [x] **v1.1.5:** Fatal Control Return (FCR) & Infrastructure stability.
- [ ] **v1.1.6:** Global Data Area (GDA) & Dedicated Memory Guard.
- [ ] **v1.1.7:** Distributed Pub/Sub Engine for decoupled communication.
- [ ] **v1.2.0:** Full PLTF/TLC Integration - The Quality Gate for μE-OS.

---

### Connect with me
<p align="left">
<a href="https://tinyurl.com/htsang1811-linkedin" target="blank"><img align="center" src="https://img.shields.io/badge/-Shang_Huang-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Huynh Thanh Sang" height="28" /></a>
<a href="mailto:htsang181105work@gmail.com" target="blank"><img align="center" src="https://img.shields.io/badge/Email-Contact_Me-c14438?style=flat-square&logo=Gmail&logoColor=white" alt="Email" height="28" /></a>
</p>
