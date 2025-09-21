# 🔧 STM32F103 Advanced Features

This repository provides modular implementations of **advanced STM32 features**:  
💾 Flash read/write • 🚀 Custom bootloader • 📡 OTA update (via ESP32/UART) • 🧩 EEPROM emulation • ✅ CRC check • ⏱️ Watchdog • ⚡ FreeRTOS support • 🔐 Secure boot • 🔌 Protocol extensions (UART/SPI/I2C/CAN).  

Designed with **scalability** and **production-ready firmware** in mind.

---

## 📂 Repository Structure  

### 🏗️ Modular Design  
- Independent modules for easy **maintenance, extension, and reuse**.  

### 💾 Flash Management  
- Read/write flash memory  
- Sector erase & page programming  
- Store and retrieve user configuration  

### 🚀 Bootloader  
- Custom bootloader support  
- Application ↔ Bootloader switching  
- Safety mechanisms (CRC, rollback)  

### 📡 OTA (Over-The-Air Update)  
- Firmware upgrade via UART, CAN, Ethernet, or Wi-Fi  
- Secure update with **encryption & integrity check**  

### 🔌 Communication Interfaces  
- UART, SPI, I2C drivers  
- CAN, Ethernet, LoRa, Zigbee (optional)  

### ⚙️ System Utilities  
- Logging & debugging tools  
- Error handling & watchdog integration  
- Task scheduling (**RTOS-ready**)  

### 🔐 Security  
- Firmware encryption  
- Secure boot support  
- Authentication mechanisms  
