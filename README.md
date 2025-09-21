# STM32F103_Advanced_Features
This repository provides implementations of advanced STM32 features such as Flash read/write, custom bootloader, OTA update via ESP32/UART, EEPROM emulation, CRC check, watchdog, FreeRTOS support, secure boot, and protocol extensions (UART/SPI/I2C/CAN). Modular design for scalable, production-ready firmware.

# Repository Structure

Modular design for scalability
Code is organized into independent modules, making it easy to maintain, extend, and reuse across projects.

Flash Management

Read/Write flash memory

Sector erase & page programming

Store and retrieve user configuration

Bootloader

Custom bootloader support

Application/bootloader switching

Safety mechanisms (CRC, rollback)

OTA (Over-The-Air Update)

Firmware upgrade via UART, CAN, Ethernet, or Wi-Fi

Secure update with encryption & integrity check

Communication Interfaces

UART, SPI, I2C drivers

CAN, Ethernet, LoRa, Zigbee (optional)

System Utilities

Logging & debugging tools

Error handling & watchdog integration

Task scheduling (RTOS ready)

Security

Firmware encryption

Secure boot support

Authentication mechanisms 
