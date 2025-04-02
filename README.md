# FPGA Projects Repository

Welcome to my FPGA Projects repository! This repository contains various FPGA-based implementations using Verilog and VHDL. These projects were developed using **Xilinx Vivado 2023.3.2** and tested on different FPGA boards like **Nexys A7, Zybo, and other Xilinx-based platforms**.

## Tools and Technologies
- **Vivado 2023.3.2** – Synthesis, Implementation, and Simulation
- **Verilog & VHDL** – RTL design
- **FPGA Boards** – Nexys A7, Zybo
- **Communication Protocols** – I2C, SPI, UART
- **Hardware Debugging** – Logic Analyzer, Signal Tap

## Projects

### 1. I2C-based Temperature Sensor (Nexys A7, ADT7420)
Developed an FPGA interface for the **ADT7420 I2C-based temperature sensor** on the Nexys A7 board, enabling real-time temperature monitoring with efficient data acquisition and processing.

### 2. SPI-based DAC (DAC121S101)
Implemented an **SPI protocol** to interface with a digital-to-analog converter (DAC) on FPGA, ensuring high-resolution signal generation and processing.

### 3. SPI-based Accelerometer (ADXL362)
Developed an FPGA-based interface for the **ADXL362 SPI accelerometer**, capturing motion and orientation data for real-time applications such as gesture recognition and vibration monitoring.

### 4. FPGA-based PS2 Keyboard Interface
Designed a **PS2 protocol interface** on FPGA for capturing keystrokes and converting them into usable input data for digital applications.

### 5. Real-time Digital Clock on VGA with Keyboard Interfacing
Implemented a **real-time clock** displayed on a **VGA screen**, integrating a keyboard interface for user-controlled time adjustments.

### 6. VGA Controller on FPGA
Designed a **VGA controller** capable of generating video signals, creating real-time graphical interfaces, and supporting custom visual displays.

### 7. OLED Interfacing on Zybo Board
Developed an **OLED display interface** on the Zybo FPGA board, enabling high-contrast graphical output and real-time data visualization.

### 8. SPI Temperature Sensor Interfacing on Zybo
Implemented an **SPI-based ADT7420 temperature sensor** on the Zybo board, enabling real-time environmental monitoring and logging.

### 9. I2C DAC on Zybo
Designed an **FPGA-based I2C digital-to-analog converter (DAC)** to generate smooth analog signals from digital inputs, enhancing real-time signal processing applications.

### 10. Interfacing PL to PS using UART and Displaying on PS I2C OLED
Designed a system where the **programmable logic (PL) communicated with the processing system (PS)** using **UART**, displaying processed data on an **OLED screen via I2C communication**.

### 11. 4x4 Keypad Interface
Designed an **FPGA-based matrix keypad decoder** that scans and detects key presses, processes the data, and transmits it to the processor.

### 12. UART Communication on FPGA
Implemented a **UART protocol** on FPGA to enable asynchronous serial communication with external devices, ensuring reliable data transmission.

### 13. Real-time Digital Clock on SSD
Developed a clock display using a **seven-segment display (SSD)**, incorporating FPGA-based timing mechanisms and multiplexing techniques.

### 14. LCD Interfacing
Successfully interfaced an **LCD display with an FPGA** to display alphanumeric characters, utilizing parallel communication for efficient data transfer.

## How to Run the Projects
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/fpga-projects.git
   cd fpga-projects
   ```
2. **Open the project in Vivado 2023.3.2**.
3. **Synthesize, Implement, and Generate Bitstream**.
4. **Program the FPGA Board and Test the Output**.

