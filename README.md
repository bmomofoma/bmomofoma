# Hi, I'm Benedict-Michael Omofoma 👋

I'm an Electrical Engineering student at California State University, Northridge (CSUN) focused on digital hardware design, ASICs/FPGAs, and embedded systems. I'm particularly interested in how we can use hardware description languages to accelerate compute for robotics and autonomous systems.

When I'm not in the engineering labs or hanging out with the IEEE crew on campus, you can usually find me hitting the gym, playing board games with friends, or catching up on anime like Bleach and Black Clover. I also have a weak spot for daily puzzles like Wordle, Sudoku, and crosswords, and I play chess from time to time.

### 🎓 Academic Journey
* **University:** California State University, Northridge (CSUN)
* **Major:** B.S. in Electrical Engineering
* **Expected Graduation:** May 2029
* **Affiliations:** IEEE CSUN Chapter Member

### 🛠️ Technical Focus
* **Digital Logic & HDLs:** Verilog, FPGA Architecture
* **EDA Tools:** KiCad (8/9)
* **Software Languages:** C, C++, Python
* **Protocols & Hardware:** I2C, SPI, UART, Multi-layer PCB Layout

### 🚀 Featured Project
* **[ESP32-S3 Sensor Hub / MRCU Rev A](https://github.com/bmomofoma/ESP32-Sensor-Interface):** A 4-layer sensor hub designed to aggregate local environmental and inertial data. It maps out a unified I2C bus for five distinct onboard sensors, handles hardware-level boot constraints, and integrates native USB-JTAG debugging.

### ⚙️ Digital Hardware IP (SystemVerilog)

* **[Async FIFO Buffer with Safe Clock Domain Crossing](https://github.com/bmomofoma/Async-FIFO):** Designed a parameterized dual-clock FIFO architecture for unsynchronized data transfer. Implemented Gray code pointer conversion and 2-stage flip-flop synchronizers to mitigate metastability and ensure accurate full/empty flag generation.
* **[OLED SPI Master Engine (Mode 0)](https://github.com/bmomofoma/SPI_Controller_Engine):** Architected a cycle-accurate, 3-wire SPI Master FSM from scratch. Optimized logic footprint by explicitly removing MISO lines for write-only displays, and engineered a parameterized clock divider to step 100MHz down to a display-safe 5MHz strobe.
