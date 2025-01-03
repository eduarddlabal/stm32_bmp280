# STM32_BMP280 Project

This project demonstrates the usage of the BMP280 sensor with an STM32 microcontroller. The project is configured using STM32CubeMX and built with CMake.

## Table of Contents
- [Introduction](#introduction)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Setup](#setup)
- [Usage](#usage)
- [References](#references)

## Introduction

The BMP280 is a barometric pressure sensor that can be used to measure atmospheric pressure and temperature. This project integrates the BMP280 sensor with an STM32 microcontroller to read and display sensor data. BMP 280 is interfaced using I2C bus.

## Hardware Requirements

- STM32F103C8T6 "BluePill" microcontroller
- BMP280 sensor module
- LCD display with I2C
- USB-UART adapter / ST-Link v2

## Software Requirements

- STM32CubeMX
- STM32CubeProgrammer
- VSCode with STM32 add-on
- CMake
- GCC ARM toolchain

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/eduarddlabal/stm32_bmp280
    cd stm32_bmp280
    ```
2. Open folder in VS Code with STM32 add-on loaded
3. Build project using "Build" button
4. Upload binary from ```build``` build directory to controller usint STM32CubeProgrammer



## References
This project uses code from the following repositories:

- [STM32_HAL_I2C_HD44780](https://github.com/eziya/STM32_HAL_I2C_HD44780) for interfacing with the HD44780 LCD display over I2C.
- [BMP280_STM32](https://github.com/ciastkolog/BMP280_STM32/tree/master) for interfacing with the BMP280 sensor.

## Notes
- please note that this README was generated by Copilot AI
- projects contains code for inteterfacing two LEDs and button, but they are not used
- if you want to use a controller other than BluePill, you must configure STM32CubeMX for it