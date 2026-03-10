# VSD DC ENERGY METER DIY KIT 
--------------------------
TEAM RANA

# INTRODUCTION  
The VSD DC Energy Meter DIY Kit is developed to measure electrical parameters such as voltage, current, power, and energy consumption in DC systems. A real-time graphical dashboard is designed using Processing software to visualize the measured data. The Processing application communicates with the DC energy meter through serial communication and displays the data in a clear and user-friendly format. This standalone approach does not require IoT or internet connectivity, making the system simple, reliable, and cost-effective for educational, laboratory, and DC energy monitoring applications.

# OVER VIEW OF PRODUCT

The VSD DC Energy Meter DIY Kit is an educational project designed to help students understand the fundamentals of DC electrical measurements, including voltage, current, power, and energy calculation. This kit provides hands-on experience in building and testing a real-time DC energy monitoring system.
The system measures DC voltage and current using appropriate sensors interfaced with a microcontroller. Based on these measurements, the kit calculates power (P = V × I) and total energy consumption over time. The real-time data is displayed on a local display and also transmitted to a computer via serial communication.
Instead of using WiFi or cloud-based IoT dashboards, this kit utilizes Processing software to create a desktop graphical interface. The Processing application visualizes voltage, current, power, and energy in real time using digital readings and dynamic graphs. This helps students clearly understand how electrical parameters change under different load conditions.

# OPERATAION OF THE SYSTEM
The DIY DC Energy Meter Kit is an educational hardware and software solution designed to measure and analyze DC electrical parameters with high accuracy. The system directly measures voltage and current using dedicated voltage and current sensors, instead of using traditional pulse-based energy measurement techniques.

To achieve higher measurement precision, the system uses a 16-bit Analog-to-Digital Converter (ADC). The 16-bit ADC provides significantly higher resolution compared to standard 10-bit or 12-bit ADCs, allowing more accurate voltage and current measurements. This improves the reliability of power and energy calculations, making the kit suitable for laboratory experiments and technical learning.
Measurement Process

The voltage sensor measures the DC supply voltage.

The current sensor measures the load current.

The analog outputs from both sensors are converted into digital values using the 16-bit ADC.

The VSD ULTRA Board processes these digital values and calculates:

Voltage (V)

Current (I)

Power (P = V × I)

Energy (E = ∑ P × Time)

# VSD Squadron Ultra Board
The VSD Squadron Ultra development board is the main controller used in the VSD DC Energy Meter DIY Kit. The board is based on the THEJAS32 RISC-V processor, which provides an open-source and efficient microcontroller platform for embedded system development.

The VSD Ultra board is designed to support educational projects, hardware experimentation, and RISC-V learning. It provides essential interfaces such as GPIO, I²C, SPI, UART, and ADC connectivity, allowing easy integration with sensors, displays, and external modules.

# THEJAS32 RISC-V Processor
The THEJAS32 is a 32-bit RISC-V based processor core designed for embedded applications. It follows the RISC-V open instruction set architecture (ISA), which provides flexibility, modularity, and scalability for custom hardware development.

Unlike proprietary microcontroller architectures, RISC-V is open-source, enabling researchers, students, and developers to study and build their own hardware systems.

Key Features of THEJAS32 Processor

32-Bit RISC-V Architecture
Provides efficient instruction execution with a reduced instruction set.

Open-Source ISA
Based on the RISC-V architecture, allowing transparent hardware and software development.

Embedded System Friendly
Optimized for low-power and real-time embedded applications.

Peripheral Interface Support
Supports communication interfaces such as UART, SPI, I²C, and GPIO.

High Processing Efficiency
Suitable for real-time monitoring systems such as energy meters, IoT devices, and sensor-based applications.


# FEATURES AND BENEFITES OF THE PRODUCT
Direct Voltage and Current Measurement
Uses dedicated DC voltage and current sensors for accurate real-time parameter monitoring.

High-Resolution 16-Bit ADC
Provides superior measurement precision compared to standard 10-bit/12-bit ADC systems.

Real-Time Power and Energy Calculation
Automatically calculates:

Voltage (V)

Current (I)

Power (P = V × I)

Energy (Wh)

LCD Display for Instant Monitoring
Displays electrical parameters locally without requiring a computer.

Processing-Based Desktop Dashboard
Real-time graphical visualization using Processing software (no internet required).

Serial Communication Interface
Enables seamless data transfer between the microcontroller and computer.

Offline Operation (No WiFi Required)
Fully functional without cloud connectivity or IoT platforms.

DIY Assembly Kit
Designed for students to assemble, test, and understand each stage of the system.

Safe Low-Voltage DC Operation
Ideal for laboratory and educational environments.



# ADVANTAGES OF THE PRODUCT
High Measurement Accuracy
The use of a 16-bit ADC provides high-resolution data acquisition, resulting in more precise voltage, current, power, and energy calculations.

Direct Sensing Method
Measures voltage and current directly instead of using pulse-based methods, making the system simpler and more transparent for learning.

Real-Time Monitoring
Provides instant display of electrical parameters on both the LCD and the Processing-based desktop dashboard.

Offline Operation
Does not require WiFi, cloud platforms, or internet connectivity, ensuring reliable performance in classrooms and laboratories.

Educational Focused Design
Specially developed as a DIY kit to help students understand practical concepts such as:

ADC resolution

Power and energy formulas

Sensor calibration

Serial communication

Cost-Effective Solution
Eliminates the need for expensive commercial DC energy meters while still providing essential measurement capabilities.

User-Friendly Visualization

<img width="1366" height="768" alt="Screenshot (329)" src="https://github.com/user-attachments/assets/c6fd6853-9f3f-47cf-9fad-dfb64c36041d" />

- Out put

![WhatsApp Image 2026-03-10 at 9 58 50 PM (1)](https://github.com/user-attachments/assets/061186c5-b00a-4106-9d70-9efe389ab4a3)

![WhatsApp Image 2026-03-10 at 9 58 50 PM](https://github.com/user-attachments/assets/01b452c7-7c3f-4a92-8d01-ef63ddc26e2e)

