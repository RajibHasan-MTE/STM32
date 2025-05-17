# 🚀 STM32 Embedded Projects Collection

Welcome to the **STM32 Embedded Projects Collection** – an open-source repository of STM32F1 and STM32F4 microcontroller projects.  
This repository is built to help students, hobbyists, and embedded engineers learn and explore the STM32 ecosystem through practical hands-on examples.

## 🧠 Microcontroller Families Used

- **STM32F103C8T6** (Blue Pill) – STM32F1 Series  
- **STM32F407VG** (Black Board) – STM32F4 Series  

All projects are developed using **STM32CubeIDE** and the **HAL (Hardware Abstraction Layer) library**.

---

## 📚 Topics Covered

This repository will cover a wide range of STM32 topics, including:

### ✅ Basic Interfaces
- GPIO (Digital Input/Output)
- ADC (Analog to Digital Converter)
- PWM (Pulse Width Modulation)
- Timers (Basic, General-purpose, and Advanced)

### 🌡️ Sensors & Peripherals
- Temperature Sensors (e.g., LM35, DHT11)
- Ultrasonic Sensor (HC-SR04)
- Infrared Sensors

### 💾 Memory Handling
- Internal Flash Read/Write
- External EEPROM via I2C/SPI
- SD Card (with FATFS)

### 📡 Communication Protocols
- UART / USART (Serial Communication)
- I2C (Inter-Integrated Circuit)
- SPI (Serial Peripheral Interface)
- CAN Bus (optional future addition)
- USB Communication (CDC, HID)

### 🖥️ Display Interfaces
- Character LCD (16x2, 20x4)
- OLED Display (SSD1306)
- TFT LCD Screens

### ⏱️ Real-Time Features
- RTC (Real-Time Clock)
- NVIC Configuration
- External and Internal Interrupts
- SysTick and Delay Functions

### 🔄 Advanced Topics (Planned)
- FreeRTOS Integration
- DMA (Direct Memory Access)
- Bootloader Development
- Low-Power Modes (Sleep, Stop, Standby)

---

## 📁 Project Structure

Organized by MCU series and functional category:

	STM32_Projects/
  	├── STM32F1/
  	│ ├── GPIO_Blink/
  	│ ├── UART_Communication/
  	│ └── ...
  	├── STM32F4/
  	│ ├── Flash_Memory_RW/
  	│ ├── Temperature_Read/
  	│ └── ...



Each folder contains source code, CubeMX `.ioc` file, and documentation (if needed).

---

## 💻 Requirements

- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)
- STM32F1 / STM32F4 development boards
- ST-Link V2 or on-board debugger
- Basic electronics components (sensors, resistors, displays, etc.)

---

## 📜 License

This repository is licensed under the [MIT License](LICENSE).  
You can use, modify, and distribute it freely for personal and academic use.

---

## 🤝 Contribute

This is an educational project. Contributions are **welcome**!
If you want to add new STM32 examples, fix bugs, or improve documentation:

1. Fork the repo
2. Create a branch (`feature/your-topic`)
3. Commit and push
4. Open a Pull Request

---

## 🙋 Contact

If you have questions, suggestions, or want to collaborate, feel free to reach out via [GitHub Issues](https://github.com/yourusername/your-repo-name/issues).

---

> **Happy Coding & Learning with STM32!** 🧠🔧⚡

