# Xuyi Zhou | Electrical & Computer Engineering @ Northwestern University

Hi! I’m Xuyi, an electrical engineering BS/MS student at Northwestern University interested in **ASIC design**, **computer architecture**, **VLSI**, **FPGAs**, and **embedded systems**. I like working close to the hardware stack — from circuit-level design and physical implementation to accelerators and firmware.

Recently, I’ve been:
- Building **Reed–Solomon accelerators** in a RISC-V SoC
- Exploring **GPU-accelerated EDA** for gate sizing
- Designing **embedded vision systems** on Raspberry Pi
- Developing **mixed-signal sensor and telemetry hardware** for Formula Racing

I’m still exploring where to specialize long-term, but I really enjoy tackling hardware problems end-to-end and learning new tools along the way.

---

## Featured Projects

### GPU-Accelerated Gate Sizing using the Held Algorithm  
**[GitHub](https://github.com/danielhufnagle/COMP_ENG-357-Final.git)** • [Paper](https://www.overleaf.com/read/pvsbfdhfkqzf#b064cc)  
- Implemented a **CUDA** version of the Held gate sizing algorithm for silicon physical design automation  
- Integrated with the **`rsz`** resizer module in **OpenROAD**  
- Achieved **~6% area reduction** on tinyRocket and **~17%** on GCD designs compared to default OpenROAD flow  
- Verified correctness using OpenROAD testbenches and documented in a 9-page technical report  

### Reed–Solomon FEC Hardware Accelerator (RoCC)  
**[GitHub](https://github.com/xuyizhou8129/RoccAcc.git)**  
- Designing a **Reed–Solomon co-processor** as a **RoCC accelerator** in a RISC-V Rocket core  
- Implemented at RTL using Verilog-based HDL within **Chipyard**, coordinating with caches and I/O in the Rocket microarchitecture :contentReference[oaicite:0]{index=0}  
- Building a full flow including Verilog generation, simulation, and performance benchmarking vs. software

### Embedded CV System — Smart Camera @ Sensify  
- Developed a **Raspberry Pi + IMX219** embedded camera system for real-time trash detection  
- Implemented **C++ frame buffering** and **OpenCV-based** classification on a Linux driver stack  
- Reduced end-to-end latency by ~30% via custom buffering and frame-selection logic :contentReference[oaicite:1]{index=1}  

### Data Acquisition Hardware — NU Formula Racing  
**[GitHub](https://github.com/NU-Formula-Racing/daq-dynamics-25.git)**  
- Designed, assembled, and tested mixed-signal PCBs for **IMU, airspeed, and flow-rate** sensors using **Altium**  
- Integrated sensor data into a **CAN-enabled DAQ** pipeline and on-car telemetry system  
- Built a **bunker monitoring system** to track real-time voltage across 12 battery modules for safe storage :contentReference[oaicite:2]{index=2}  

---

## Research & Experience

### Parallel Architecture Group @ Northwestern — Research Assistant  
- Designing a **Reed–Solomon hardware accelerator ASIC** integrated into a RISC-V CPU pipeline  
- Implementing the co-processor at RTL within **Chipyard**, interfacing with memory hierarchies and I/O  
- Running performance tests using **Verilator**, **FireSim**, and FPGA boards; achieving up to **100× speedup** over software testbenches :contentReference[oaicite:3]{index=3}  

### Nanoscale Spintronic Devices — Northwestern University  
- Fabricated **Fe₃GaTe₂ Hall bar devices** and layered structures via maskless lithography  
- Performed low-temperature transport measurements to study **ionic gating effects** in spintronic materials  
- Wrote Python scripts for electrical and magnetic data analysis used in a poster presentation :contentReference[oaicite:4]{index=4}  

### Organic Semiconducting Nanocomposites — Garcia Program @ Stony Brook  
- Engineered an organic flame-retardant nanocomposite with controlled electrical and thermal properties  
- Co-designed experiments, characterized material performance, and authored a **first-author abstract** accepted to **MRS Fall 2023** :contentReference[oaicite:5]{index=5}  

---

## Technical Skills

- **Programming & Frameworks**  
  Python, C/C++, Verilog, Chisel, Scala, CUDA, MATLAB, LaTeX

- **Hardware & Embedded Systems**  
  ASIC design, SoC development (**Chipyard**, Rocket Core integration),  
  Embedded systems (Raspberry Pi, Arduino, ESP32), IMX219 camera integration, USB/UART

- **Physical & PCB Design**  
  OpenROAD (physical design and resizer integration),  
  Altium Designer, mixed-signal PCB design and soldering, maskless lithography

- **Computer Vision, Signal Processing & Data Acquisition**  
  OpenCV, Linux camera driver stack (V4L2), sensor interfacing, DAQ, CAN-based telemetry

- **Tools & Environments**  
  Linux/Unix, Git, Make, SBT, shell scripting, oscilloscopes, logic analyzers, gtkWave

---

## Contact

- 📱 773-461-8464  
- 📧 XuyiMikeZhou@gmail.com  
- 💼 [LinkedIn](https://www.linkedin.com/in/mikexyz/)
