# Hey, I'm Jacob 👋

### RTL, RISC-V, and the occasional 01100101 01110010 01110010 01101111 01110010.

I'm **Jacob Torry**, an Electrical & Computer Engineering student at the **University of Illinois Urbana-Champaign**, focused on **RTL design, FPGA development, and computer architecture**.

I build digital systems in Verilog/SystemVerilog—from sending a byte over UART to getting instructions through an out-of-order processor. I enjoy the whole process: sketching the architecture, writing the RTL, and finding out what the waveform has to say about my assumptions.

- Expected graduation: December 2026
- Currently building **Project KHONSU**, an out-of-order RISC-V processor project targeting the Urbana FPGA.
- Interested in RTL Design / FPGA Engineering / Design Verification / CPU Architecture / SystemVerilog.
- Away from the waveforms: Formula 1, LEGO, custom PCs, soccer, The Simpsons.

## Things I've Built

### RISC-V Processor Projects · ECE 411

*From five pipeline stages to instructions executing out of order.*

A progression of SystemVerilog designs covering a five-stage processor, a parameterized cache subsystem, and a Tomasulo-style out-of-order core.

- **Pipeline:** hazard detection, forwarding, stalls, and branch flushes.
- **Memory:** configurable cache geometry, write-back/write-allocate behavior, and tree-PLRU replacement.
- **Out-of-order execution:** register renaming, reservation stations, a reorder buffer, and a split load/store queue with store-to-load forwarding.
- **Verification:** Spike reference checking and RVFI monitoring, with VCS/Verdi for simulation and debugging.

**Result I'm proud of:** Achieving the highest frequency (666 MHz) on our out-of-order RISC-V core in a class of about 50 groups.

📂 Repository: [\[RISC-V REPOSITORY URL\]](https://github.com/jacobmtorry/Computer-Architecture)

### UART on FPGA

*One byte, one round trip, a lot of timing.*

Built a SystemVerilog UART on the Urbana FPGA, progressing from individual modules to a working **PC → FPGA → PC echo path**.

- Implemented baud-rate generation and independent TX/RX state machines using **8N1 framing**.
- Wrote self-checking simulations for timing, transmitted frames, received bytes, and TX-to-RX loopback.
- Demonstrated FPGA loopback and PC serial echo at **115200 baud**, including the effects of a baud-rate mismatch.

📂 Repository: [\[UART REPOSITORY URL\]](https://github.com/jacobmtorry/UART) 

### FPGA Pac-Man · ECE 385

*Chasing ghosts, debugging pixels.*

An FPGA implementation of Pac-Man combining custom display hardware with MicroBlaze software, developed with **Logan Wonnacott**.

- Hardware text/tile rendering and VGA/HDMI output.
- USB keyboard input, ghost behaviors, pellets, power-ups, and score tracking.
- An **AXI4-Lite interface** connecting MicroBlaze game logic to the custom display peripheral.


📂 Repository: [\[PAC-MAN REPOSITORY URL\]](https://github.com/jacobmtorry/Pacman) · 🎬 [Watch the demo](https://www.youtube.com/watch?v=ORMuu2yWL28&t=17s)

## On the Workbench: Project KHONSU

*The goal: a processor you can watch think.*

An ongoing team project with **Samuel Slaw**, targeting an **out-of-order RISC-V processor on the Real Digital Urbana Spartan-7 FPGA**. The planned HDMI dashboard will visualize registers, memory, instruction history, and performance metrics.

**Working now:** Docker development environment, passing RTL smoke test, and verified RV32I software compilation.

**Up next:** processor integration, Spike-based reference checking, FPGA bring-up, DDR3 integration, and the HDMI dashboard.

**My focus:** Currently developing fetch stage.

📂 Repository: [\[KHONSU REPOSITORY URL\]](https://github.com/jacobmtorry/KHONSU)

## 🛠️ My Toolbox

| Area | Languages & Tools |
| --- | --- |
| RTL & digital design | SystemVerilog, Verilog, VHDL |
| FPGA development | Vivado, Vitis, Urbana FPGA |
| Simulation & debug | VCS, Verdi, Verilator, GTKWave, Surfer |
| Processor verification | Spike, RVFI, custom testbenches |
| Supporting software | C, Python, RISC-V assembly |
| Development environment | Linux, Docker, Git |

**Currently learning:** CPU Architecture, writing clean functional verilog

## 🤝 Let's Connect

I'm happy to talk about processor design, FPGA projects, or The Simpson.

- [LinkedIn](https://linkedin.com/in/jacobtorry)
- [Portfolio Website](https://jacobmtorry.github.io/)

---

*Simulate. Inspect waveforms. Find the bug. Repeat.*
