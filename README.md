<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:312E81,45:5B21B6,100:7C3AED&height=220&section=header&text=Md%20Reajul%20Karim%20Hridoy&fontSize=38&fontColor=FFFFFF&fontAlignY=36&desc=Hardware%20Security%20%7C%20Computer%20Architecture%20%7C%20RTL%20%7C%20FPGA&descAlignY=57&descSize=18&animation=fadeIn" alt="Profile header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=A78BFA&center=true&vCenter=true&width=920&lines=Hardware+%26+SoC+Security+%7C+RISC-V+%7C+Computer+Architecture;SystemVerilog+%7C+UVM+%7C+SVA+%7C+Functional+Coverage;RTL+Design+%7C+AMBA+AXI%2FAPB+%7C+FPGA+Prototyping;Logic+Locking+%7C+Hardware+Trojan+Detection+%7C+Hardware+Trust;ASIC+Design+%7C+Physical+Design+%7C+AI+for+EDA" alt="Typing animation" />
</p>

<p align="center">
  <a href="https://www.ruet.ac.bd/">
    <img src="https://img.shields.io/badge/B.Sc._EEE-RUET-5B21B6?style=for-the-badge" alt="RUET" />
  </a>
  <img src="https://img.shields.io/badge/Dhaka-Bangladesh-4338CA?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=hridoy7862&label=Profile%20Views&color=6D28D9&style=for-the-badge" alt="Profile views" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/md-reajul-karim-hridoy-8a96b9362/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:md.hridoy7862@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/hridoy7862?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositories-312E81?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repositories" />
  </a>
</p>

---

## About

I am an **RTL Design & Verification Engineer** with a B.Sc. in Electrical & Electronic Engineering from **Rajshahi University of Engineering & Technology (RUET)**. My technical and research interests lie at the intersection of **hardware security, computer architecture, RTL design and verification, FPGA prototyping, and VLSI/ASIC design**.

My work spans both **hardware implementation and verification**, including RISC-V processor and SoC architectures, AMBA interconnects, memory and CDC structures, SystemVerilog RTL, UVM and class-based verification, FPGA implementation, and ASIC physical design.

I am particularly interested in understanding how secure and reliable computing systems can be designed from the **architecture level down to RTL and physical implementation**.

---

## Research Interests

- **Hardware & SoC Security**
- **Computer Architecture & SoC Design**
- **RTL Design & Verification**
- **FPGA Architecture & Prototyping**
- **VLSI & Digital IC Design**
- **ASIC Design & Physical Design**
- **Hardware Trust**
- **Logic Locking & SAT-Based Attacks**
- **Hardware Trojan Detection**
- **Embedded Systems**
- **AI for EDA**

---

## Research Experience

### 🔐 IP Protection in SoCs — Logic Locking Evaluation with SAT Attacks

**B.Sc. Thesis — Rajshahi University of Engineering & Technology**

- Investigated **logic locking** techniques for protecting hardware IP in System-on-Chip (SoC) designs.
- Analyzed the vulnerability of conventional locking schemes to **SAT-based attacks**.
- Developed an algorithm from the **attacker perspective** to analyze and break logic-locked circuits.
- Developed **two protection algorithms** from the defender perspective to improve resistance against SAT-based attacks.
- Evaluated the proposed protection approaches against the developed attack methodology.

**Research Themes:**  
`Hardware Security` `Logic Locking` `SAT Attacks` `IP Protection` `SoC Security`

---

### 🔐 Mole — GPU Trusted Execution Environment Security

**Independent Research Project**

- Studied the **Mole attack** against GPU Trusted Execution Environments (TEEs).
- Investigated how compromised GPU-embedded microcontrollers can undermine trusted execution.
- Analyzed the security assumptions and architectural trust boundaries involved in GPU TEEs.
- Examined implications for **hardware-assisted security, GPU security, and secure SoC architectures**.

**Research Themes:**  
`GPU Security` `Trusted Execution Environments` `Hardware Security` `Embedded Microcontrollers`

---

# RISC-V & Computer Architecture

## 🚀 CVA6 RISC-V Processor SoC — Artix-7 FPGA

- Studied the **CVA6 (Ariane) open-source RISC-V processor architecture**, including its six-stage pipeline and cache/memory subsystem.
- Analyzed processor execution stages including instruction fetch, decode, issue, execute, and commit.
- Integrated and implemented the open-source CVA6 SoC on an **Artix-7 FPGA** using Vivado.
- Completed synthesis, implementation, timing/constraint handling, and bitstream generation.
- Brought up the processor on physical FPGA hardware and executed programs to validate the implementation.

**Technologies:**  
`RISC-V` `CVA6` `SystemVerilog` `Vivado` `Artix-7` `FPGA`

[View Project](https://github.com/hridoy7862/cva6_FPGA_implementation)

---

## 🚀 Pulpissimo RISC-V SoC — ZedBoard FPGA Bring-Up

- Studied the architecture and integration of the **Pulpissimo 4-stage open-source RISC-V SoC**.
- Implemented the SoC on a **Digilent ZedBoard** using the Vivado FPGA implementation flow.
- Worked through synthesis, implementation, constraints, and bitstream generation for FPGA deployment.
- Established **JTAG-based program loading/debugging** and executed RISC-V programs on the FPGA-hosted SoC.

**Technologies:**  
`RISC-V` `Pulpissimo` `SoC` `Vivado` `ZedBoard` `JTAG` `FPGA`

[View Project](https://github.com/hridoy7862/pulpissimo_soc_fpga_zedboard)

---

# RTL Design & Verification

## 🔌 AXI Bus Architecture Design & UVM Verification

Designed and verified an AXI-based interconnect architecture in SystemVerilog.

### Architecture

- Independent AXI read and write channels
- VALID/READY handshaking
- Address and data routing
- Response handling
- Arbitration
- Transaction ordering
- Burst-based read/write transactions
- Master/slave communication

### RTL

- Developed synthesizable SystemVerilog RTL for AXI master/slave and interconnect functionality.
- Implemented channel-level control and transaction management.
- Designed and verified multi-master/multi-slave communication scenarios.

### Verification

Developed both **class-based and UVM verification environments** containing:

```text
Test
  │
  └── Environment
        │
        ├── Agent
        │     ├── Driver
        │     └── Monitor
        │
        ├── Reference Model
        │
        └── Scoreboard
