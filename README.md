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

Verification included:

Directed testing
Constrained-random stimulus
Transaction-level checking
Self-checking scoreboards
Reference models
Functional coverage
SystemVerilog Assertions
Protocol and corner-case testing
Regression/debug analysis

Technologies:
SystemVerilog UVM AXI RTL Constrained Random SVA Functional Coverage

🔌 APB Bus Architecture Design & UVM Verification
Designed and implemented an APB master/slave communication architecture in SystemVerilog.
Implemented address, control, read/write data, transfer sequencing, and response logic.
Developed synthesizable RTL for APB communication and address decoding.
Built both class-based and UVM verification environments.
Developed drivers, monitors, reference models, scoreboards, sequences, and self-checking tests.
Verified read/write transactions, address decoding, transfer sequencing, response behavior, and error scenarios.
Deployed the RTL implementation on an FPGA board.

Technologies:
SystemVerilog UVM APB RTL Verification FPGA

View Project

🧮 RV32I 5-Stage Processor Design & Verification

A SystemVerilog implementation and verification environment for an in-order RV32I processor.

Microarchitecture
IF / ID / EX / MEM / WB pipeline
Data forwarding
Load-use stall handling
Branch and jump redirection
Control-hazard flushing
Instruction retirement checking
Verification
Instruction-aware stimulus
Commit/retirement monitoring
Independent architectural reference model
Self-checking scoreboard
Functional coverage
SystemVerilog Assertions
Constrained-random verification
Results
Zero scoreboard mismatches across more than 20,000 retired instructions
77% functional coverage in the documented verification phase

The retirement-level verification strategy separates architectural correctness from internal pipeline timing and helps expose forwarding, stall, flush, writeback, and control-flow defects.

View Project

🔗 AXI4-Crossbar to APB Bridge Design & Verification

A synthesizable protocol bridge translating AXI traffic into APB transactions.

RTL
AXI read/write channel handling
APB setup/access phases
PREADY wait-state propagation
Response generation
Error response mapping
Transaction sequencing
Dynamic Verification
Transaction-level driver
Passive monitor
Self-checking scoreboard
Functional coverage
Directed tests
Constrained-random traffic
Error injection
Formal Verification

Used SystemVerilog Assertions and SymbiYosys-based formal verification for properties covering:

Protocol sequencing
State transitions
Response correctness
Signal stability
Selected datapath invariants
Regression
Makefile-driven simulation
Automated test execution
Per-test logs
Pass/fail reporting
Normal, stalled, and invalid-access scenarios

View Project

FPGA & Digital Design Projects
🧮 Asynchronous FIFO Design & CDC Verification
Designed a dual-clock asynchronous FIFO in SystemVerilog.
Implemented Gray-coded read/write pointers for safe clock-domain crossing.
Used two-flop synchronizers for pointer synchronization.
Developed a class-based verification environment.
Verified simultaneous read/write operations, full/empty behavior, and CDC corner cases.

Technologies:
SystemVerilog CDC Gray Code FIFO Class-Based Verification

View Project

🧮 Synchronous FIFO Design & Verification
Designed a parameterized synchronous FIFO RTL.
Verified full and empty conditions.
Tested overflow and underflow behavior.
Verified pointer wrap-around.
Tested concurrent read/write operations.
Developed self-checking verification scenarios.

View Project

Hardware Security
🛡️ FSM-Based Hardware Trojan Detection in PicoRV32 SoC
Designed an FSM-based hardware Trojan detection mechanism for the PicoRV32 RISC-V SoC.
Integrated the detection logic into the SystemVerilog design.
Developed simulation testbenches to exercise normal and malicious operating conditions.
Evaluated the behavior of the detection mechanism under different operating scenarios.

Technologies:
RISC-V PicoRV32 SystemVerilog Hardware Security Hardware Trojan Detection

ASIC & Physical Design

My professional experience also includes hands-on exposure to the backend ASIC physical-design flow.

Physical Design
Floorplanning
Placement
Clock Tree Synthesis
Routing
DRC
LVS
Static Timing Analysis
Post-route timing analysis
RTL / Verification
SystemVerilog RTL
UVM
Class-based verification
AXI
APB
FIFO
CDC
Assertions
Functional coverage
FPGA
Xilinx Vivado
XSIM
Synthesis
Implementation
XDC constraints
Timing analysis
Bitstream generation
Artix-7
Zynq / ZedBoard
JTAG-based FPGA bring-up
Technical Stack
Languages
<p align="center"> <img src="https://skillicons.dev/icons?i=c,cpp,python,linux,git,github,vscode&theme=dark" alt="Languages and tools" /> </p> <p align="center"> <img src="https://img.shields.io/badge/Verilog-HDL-5B21B6?style=flat-square" alt="Verilog" /> <img src="https://img.shields.io/badge/SystemVerilog-RTL_%26_Verification-6D28D9?style=flat-square" alt="SystemVerilog" /> <img src="https://img.shields.io/badge/VHDL-HDL-4F46E5?style=flat-square" alt="VHDL" /> <img src="https://img.shields.io/badge/Python-Automation-4338CA?style=flat-square" alt="Python" /> <img src="https://img.shields.io/badge/C%2FC%2B%2B-Programming-7C3AED?style=flat-square" alt="C/C++" /> </p>
Verification
<p align="center"> <img src="https://img.shields.io/badge/UVM-Verification-5B21B6?style=for-the-badge" alt="UVM" /> <img src="https://img.shields.io/badge/SVA-Assertions-4F46E5?style=for-the-badge" alt="SVA" /> <img src="https://img.shields.io/badge/Functional_Coverage-Coverage_Closure-7C3AED?style=for-the-badge" alt="Functional Coverage" /> <img src="https://img.shields.io/badge/Constrained_Random-Stimulus-6D28D9?style=for-the-badge" alt="Constrained Random" /> <img src="https://img.shields.io/badge/Formal_Verification-SymbiYosys-4338CA?style=for-the-badge" alt="Formal Verification" /> </p>
Architecture & Protocols
<p align="center"> <img src="https://img.shields.io/badge/RISC--V-Processor_%26_SoC-5B21B6?style=flat-square" alt="RISC-V" /> <img src="https://img.shields.io/badge/AMBA-AXI_%7C_APB-4F46E5?style=flat-square" alt="AMBA" /> <img src="https://img.shields.io/badge/RTL-FSM_%7C_Pipeline_%7C_Arbitration-6D28D9?style=flat-square" alt="RTL" /> <img src="https://img.shields.io/badge/Memory-Cache_%7C_SRAM_%7C_FIFO-4338CA?style=flat-square" alt="Memory" /> </p>
FPGA & EDA
<p align="center"> <img src="https://img.shields.io/badge/Vivado-FPGA_Flow-7C3AED?style=flat-square" alt="Vivado" /> <img src="https://img.shields.io/badge/XSIM-Simulation-6D28D9?style=flat-square" alt="XSIM" /> <img src="https://img.shields.io/badge/Artix--7-FPGA-5B21B6?style=flat-square" alt="Artix-7" /> <img src="https://img.shields.io/badge/Zynq-ZedBoard-4F46E5?style=flat-square" alt="ZedBoard" /> <img src="https://img.shields.io/badge/JTAG-FPGA_Bring--Up-4338CA?style=flat-square" alt="JTAG" /> </p>

Engineering & Verification Approach
Architecture / Specification
            ↓
     Design Decomposition
            ↓
       RTL Development
            ↓
      Verification Plan
            ↓
  Stimulus + Driver + Monitor
            ↓
 Reference Model + Scoreboard
            ↓
 Assertions + Functional Coverage
            ↓
 Directed + Constrained-Random Tests
            ↓
    Regression & Debug
            ↓
 Simulation / Formal Validation
            ↓
      FPGA Implementation
            ↓
      Hardware Bring-Up
Verification Principles
Treat assertions as executable interface and microarchitecture requirements.
Keep scoreboards and reference models independent from DUT implementation details wherever practical.
Verify backpressure, reset behavior, error propagation, illegal behavior, and corner cases—not only nominal traffic.
Use functional coverage to identify missing scenarios rather than treating coverage as a substitute for correctness.
Use waveform analysis, transaction tracing, and assertion failures for root-cause debugging.
Validate designs progressively from RTL simulation through synthesis, implementation, and FPGA hardware when applicable.
Current Technical Focus
research:
  - Hardware and SoC Security
  - Computer Architecture
  - RISC-V Systems
  - RTL Design and Verification
  - FPGA Architecture and Prototyping
  - Hardware Trust
  - Logic Locking
  - Hardware Trojan Detection
  - AI for EDA

building:
  - Deeper RISC-V and SoC architecture knowledge
  - Advanced UVM verification environments
  - Assertion-based and coverage-driven verification
  - FPGA-based SoC prototyping
  - Hardware-security research foundations
  - ASIC and physical-design expertise
Education
Bachelor of Science in Electrical & Electronic Engineering

Rajshahi University of Engineering & Technology (RUET)
2019 – 2025
CGPA: 3.39 / 4.00
CGPA over last 40 credits: 3.88 / 4.00

Connect
<p align="center"> <a href="mailto:md.hridoy7862@gmail.com"> <img src="https://img.shields.io/badge/Gmail-md.hridoy7862%40gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /> </a> <a href="https://www.linkedin.com/in/md-reajul-karim-hridoy-8a96b9362/"> <img src="https://img.shields.io/badge/LinkedIn-Md_Reajul_Karim_Hridoy-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /> </a> <a href="https://github.com/hridoy7862"> <img src="https://img.shields.io/badge/GitHub-hridoy7862-312E81?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /> </a> </p>
