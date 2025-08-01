# 👋 Hi, I’m Amandeep Singh

I'm a recent graduate from **UC Riverside** with a B.S. in **Computer Engineering**, passionate about embedded systems, control systems, and real-time hardware/software integration.

I'm looking for opportunities in **Embedded Systems**, **Controls Engineering**, or **Embedded Software Development**, and love building systems that bridge low-level hardware with high-level logic.

---

## 🛠️ Technical Skills

- **Languages:** C, C++, Python (Proficient) | Verilog, SQL, HTML/CSS, JavaScript, MATLAB, CUDA (Familiar)  
- **Microcontrollers & Platforms:** ESP32, Jetson Nano, Raspberry Pi, NXP K64F, ATmega328P  
- **Tools & Frameworks:** Git, Linux, Docker, PyCUDA, Flask, YOLOv5/v8, Make, LabVIEW, PSpice, Cadence OrCAD, Fusion 360, GTKWave
- **Instrumentation:** Digital Multimeter, Soldering, Signal Generators, Spectrum Analyzers, Logic Analyzers  
- **Interfaces & Protocols:** UART, SPI, I²C, GPIO, ADC, PWM, MQTT

---

## 🚀 Projects

### 🔍 Autonomous Reconnaissance Vehicle [https://github.com/k-main/RC-Car]
Senior Design Capstone @ UCR  
**Technologies:** ESP32, NRF24L01, LiDAR, GPS, Servo Control, Custom Chassis

A rugged, remote-controlled, and semi-autonomous vehicle designed for use in disaster zones and remote exploration.

- Designed and built a modular, battery-powered robotic vehicle for autonomous navigation and remote reconnaissance in hazardous environments.
- Collaborated in a 5-member Agile team to deliver a robust prototype, resolving challenges in integration, robustness, redundancy, and safety.
- Developed embedded software for ESP32 microcontrollers to handle motor control, GPS/accelerometer sensor fusion, wireless communication, and autonomous path planning.
- Implemented the **LiDAR subsystem** for 360° obstacle detection using dual Time-of-Flight sensors and servos
- Engineered wireless control via NRF24L modules, enabling bidirectional communication between handheld controller and vehicle subsystems.
- Performed extensive subsystem and integration testing on motor drivers, wireless links, autonomous driving algorithms, and sensor calibration.
- Delivered: a functional prototype supporting manual and autonomous modes with modular architecture for future upgrades.
- Completed all deliverables under tight academic deadlines, demonstrating strong project planning, engineering documentation, and technical execution
- Authored professional engineering documentation, including:
  - **Project Briefing**, **Requirements Specification**, and **Testing Strategy**
  - A complete engineering **Report** with **system architecture**, **constraints**, **definitions**, and **future development plans**

---

### 🐾 Automatic Pet Feeder [https://github.com/AmandepSingh180d/Automatic-Pet-Feeder.git]
**Technologies:** C, GPIO, ADC, Stepper Motors, Register-level Programming

An embedded pet feeder with configurable modes and portion control via analog inputs using a Bare-metal K64F

- Designed and built an automatic pet feeder on the NXP K64F microcontroller using low-level register programming for GPIO, ADC, and timer modules.
- Collaborated in a 2-member team to build, debug, and validate system behavior through iterative testing and circuit refinement.
- Implemented mode selection via potentiometers, photoresistor-based food level sensing, and stepper motor control for dispensing.
- Programmed multiple operating modes—manual, timed, and portion-controlled—using a modular architecture in embedded C.
- Engineered a physical prototype with LEDs and sensors for user feedback, optimizing ADC input allocation under hardware constraints.

---

### 🛡️ Smart Security System [PRIVATE REPO]
**Technologies:** Jetson Nano, YOLOv8, MQTT, Flask, Docker, Raspberry Pi

An AI-powered security system with motion-based detection, live notifications, and private VPN-secured dashboard access.

- Designed and implemented a smart home security system integrating Jetson Nano, Raspberry Pi, and a self-hosted cloud backend for real-time surveillance and intrusion detection.
- Collaborated in a 4-member Agile team to deliver a robust prototype, resolving challenges in video buffering, message deduplication, and system state consistency.
- Developed and deployed embedded software to perform real-time object detection using YOLOv8 models on the Jetson Nano for accurate classification of human motion versus pets.
- Engineered secure communication protocols using MQTT over QoS, TLS, and Tailscale VPN to enable encrypted data transmission and private device networking.
- Built a user-friendly interface on the Raspberry Pi for arming/disarming, alarm triggering, and reviewing event logs with minimal latency.
- Designed a resilient system architecture with local storage fallback and state synchronization to maintain continuous operation during network outages.

---

### ⚡ Jetson Nano YOLOv5 GPU Optimization [PRIVATE REPO]
**Technologies**: CUDA, C++, Cython, Python, Jetson Nano, YOLOv5

A real-time object detection pipeline optimized for the Jetson Nano using custom CUDA kernels and performance profiling.

- Achieved up to 18% improvement over baseline YOLOv5 by rewriting Non-Maximum Suppression (NMS) and Bounding Box Decoding directly in CUDA
- Collaborated in a 2-member team using incremental programming
- Replaced Python-bound inference steps with low-level memory-optimized GPU kernels
- Used Cython and PyCUDA to integrate CUDA kernels into the Python YOLOv5 inference pipeline
- Implemented detailed timing benchmarks to validate per-frame performance improvements
- Compared custom pipeline to TorchScript baseline to verify gains under real-world inference scenarios

---

---

### 🎮 RPG Game (CS100) [https://github.com/AmandepSingh180d/FinalProjectCS100UCR.git]
**Technologies**: Linux, C++

A turn-based, multiplayer fantasy RPG game featuring class-based characters, strategic combat, alliances, and inventory systems — all running in a C++ console environment.

- Designed combat mechanics and player classes, built the core turn-based battle loop, and integrated character movement and event systems.
- Worked in an Agile team of 4, following sprint-based development with regular stand-ups and code reviews
- Implemented class-based characters (Knight, Mage, Archer, Cleric), each with unique abilities and stats
- Contributed to the PlayerManager system, enabling real-time combat, alliances, and win-condition tracking
- Built modular inventory and action systems following SOLID principles and clean interface segregation
- Designed intuitive menu-based UI for game control, combat decisions, and player interactions
- Integrated GoogleTest for test-driven development of core mechanics (combat flow, damage calculations, item logic)

---

### 🎶 MP3 Player [https://github.com/AmandepSingh180d/MP3-Player-Project.git]
**Technologies**: C/C++, Arduino Uno, Tone library, Joystick, LCD

An embedded MP3 player simulator that plays preset melodies using buzzer output and a joystick-driven menu interface.

- Implemented incremental development via code and hardware, with many testing phases along the way
- Developed a state-machine-based task scheduler to handle LCD rendering, joystick input, tone generation, and playback control
- Implemented joystick navigation logic for song selection, pause/resume, and back functionality
- Designed a multi-screen LCD interface with cursor movement using an analog joystick and a physical select button
- Wrote modular C code to improve maintainability; optimized variable usage and interface logic
- Supported three custom songs represented as note-frequency arrays with corresponding time durations, with the ability to add custom songs easily

---

### ⚙️ Additional Technical Projects  
_Reach out if you'd like more details on any of these topics!_

- 🗃️ **Relational Database Design**  
  Wrote and optimized SQL queries for a Pizza Store management system, including order processing and customer/driver/store relations.

- ⚡ **Analog Circuit Design**  
  - Designed and simulated **Common-Emitter Amplifiers** with mid-band gain targeting  
  - Built and analyzed **Current Mirrors** and **Cascode structures** for improved output resistance and stability  
  - Implemented **Differential Amplifiers** with **Active Loads** for precise differential-to-single-ended signal conversion  
  - Applied **Negative Feedback** in **Op-Amp configurations** for gain control and bandwidth shaping  
  - Developed and tested **Feedback-Based Voltage Regulators** for supply stabilization


---

## 📫 Let’s Connect!

- [LinkedIn](https://www.linkedin.com/in/amandeep-singh-428061230)  
- 📧 amandeepsingh180d@gmail.com

---
