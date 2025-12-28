# Xuyi Zhou | Electrical & Computer Engineering @ Northwestern University

Hi! I’m Xuyi, an electrical engineering BS/MS student at Northwestern University interested in **ASIC design**, **computer architecture**, **VLSI**, **FPGAs**, and **embedded systems**. I like working close to the hardware stack — from circuit-level design and physical implementation to accelerators and firmware.

Recently, I’ve been:
- Building **Reed–Solomon accelerators** in a RISC-V SoC
- Developing **mixed-signal sensor and telemetry hardware** for Formula Racing
- Exploring **GPU-accelerated EDA** for gate sizing
- Designing **embedded vision systems** on Raspberry Pi

I’m still exploring where to specialize long-term, but I really enjoy tackling hardware problems end-to-end and learning new tools along the way.

---

## Work Experience

### Reed–Solomon FEC Hardware Accelerator (RoCC) - Parallel Architecture Group @Northwestern
**[GitHub](https://github.com/xuyizhou8129/RoccAcc.git)**  
- Designing a Reed-Solomon **hardware accelerator ASIC** in **RISC-V CPU** to enhance data recovery capabilities
- Implemented co-processor at **RTL level** using Verilog-based HDL within Chipyard SOC, coordinating with memory hierarchies and I/O interfaces in Rocket Core microarchitecture with ensured system compatibility
- Conducting over **10 critical performance tests** in Linux environment using Verilator and Firesim simulators and FPGA boards, achieved a **100x speed** on self-developed testbench compared to software implementations

### Data Acquisition Hardware & Bunker Monitor — NU Formula Racing  
**[GitHub](https://github.com/NU-Formula-Racing/daq-dynamics-25.git)**  
- Designed and assembled mixed-signal IMU, airspeed, and flow-rate sensor circuits for acceleration, aerodynamic, and coolant monitoring, using Altium for PCB logic and layout design and C++ for firmware
- Conducted **5 critical performance and quality tests** and achieved a **20% upgrade** coolant detection accuracy
- Designed a bunker monitoring system tracking 12 battery modules with real-time voltage sensing for safe storage
- Developed a **USB-to-UART bridge PCB** enabling 12 Mbps data transfer between MCU and accumulator
- Implemented firmware in C and data-handling logic to stream real-time telemetry to a cloud-hosted dashboard

### Embedded CV System — Smart Camera @ Sensify Inc.
- Developed a Raspberry Pi–based embedded smart camera system for real-time trash detection with IMX219 sensor, classification using OpenCV image processing, and data logging through AWS platform
- Achieved a **30% improvement** in latency in performance analysis by implementing buffering logic using Linux driver stack in C++ firmware with an emphasis on frame selection algorithm

---

## Projects

### GPU-Accelerated Gate Sizing using the Held Algorithm  
**[GitHub](https://github.com/danielhufnagle/COMP_ENG-357-Final.git)** • [Paper](https://www.overleaf.com/read/pvsbfdhfkqzf#b064cc)  
- Implemented a parallelized version of the Held algorithm gate sizing in silicon physical design automation, achieved a **6% reduction** in total design area for the **tinyRocket chip** and **17%** for the GCD chip
- Integrated CUDA implementation with the OpenROAD resizer and conducted verification with built-in testbenches

### Interpretable FPGA Power Estimation by Greedy Boosting and Feature Expansion
**[GitHub](https://github.com/xuyizhou8129/fpga-power-estimator)** • [Paper](https://www.overleaf.com/project/691162af603b1a669403d144)  
- Developed a nonlinear boosting model based on machine learning for FPGA power prediction, achieving **87% test accuracy** within ±10% error and reducing test RMSE by **19%** over a linear baseline
- Identified and ranked dominant power drivers (DSP, BRAM, LUT) to improve model interpretability

### Nanoscale Spintronic Devices — Northwestern University  
- Designed suing AutoCAD and Fabricated **Fe₃GaTe₂ Hall bar devices** and layered structures via maskless lithography  
- Performed low-temperature transport measurements to study **ionic gating effects** in spintronic materials  
- Completed Python scripts for electronic and magnetic properties data analysis used for poster presentation

### Organic Semiconducting Nanocomposites — Garcia Program @ Stony Brook  
- Engineered an organic flame-retardant nanocomposite with electrical and thermal conductivity via 3D printing
- Produced an abstract and accepted for **Materials Research Society 2023 Conf. as 1st author**

---

## Contact

- 📱 773-461-8464  
- 📧 XuyiMikeZhou@gmail.com  
- 💼 [LinkedIn](https://www.linkedin.com/in/mikexyz/)
