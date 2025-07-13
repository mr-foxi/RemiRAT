# RemiRAT: Versatile Open-Source Wireless Control & Automation Platform
The RemiRAT is a custom PCB that integrates the power of an Arduino Due (SAM3X8EA-AU) with the wireless capabilities of an ESP32-WROOM-32UE-N16 onto a single, compact board. This unified platform condenses complex, multi-board development setups into a streamlined solution, enhancing integration and reliability for advanced control and automation projects.

## Key Features:

Dual Microcontrollers: Combines the SAM3X8EA-AU for high-performance real-time tasks and extensive I/O (including DMA for efficient data handling and RTC support for accurate time-keeping) with the ESP32 for seamless Wi-Fi/Bluetooth connectivity and cloud integration, supporting an external antenna for optimal range.

Robust Industrial Communication: Features dedicated CANBUS (SN65HVD230DR) and MODBUS-RS485 (MAX485CSA+T) transceivers, ensuring reliable data exchange in industrial, automotive, and other demanding environments, complete with proper termination and failsafe biasing for signal integrity.

Diverse Peripherals: Offers comprehensive Digital and Analog I/O, supporting common protocols like UART, SPI, I2C, PWM, and includes a MicroSD card slot for flexible data logging and storage.

Flexible Power Management: Accepts a broad 6.5-32V input via a robust barrel jack or screw terminal, or via USB-C for convenience. It features efficient multi-stage regulation providing stable 5V and 3.3V outputs, backed by integrated fuse protection and USB ESD protection for enhanced durability.

Developer Friendly: Provides multiple options for easy firmware development, including UART, JTAG, and SWD flashing capabilities for both MCUs, along with an ESP32 boot mode DIP switch and clearly labeled breakout headers.

RemiRAT stands as a powerful, robust, and highly integrated solution for tackling complex wireless control and IoT applications with confidence.
