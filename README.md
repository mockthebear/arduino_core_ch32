# Arduino core support for CH32 EVT Boards

* [Introduction](https://github.com/openwch/arduino_core_ch32#Introduction)<br>
* [How to use](https://github.com/openwch/arduino_core_ch32#How-to-use)<br>
* [Supported boards](https://github.com/openwch/arduino_core_ch32#Supported-boards)<br>
* [Submit bugs](https://github.com/openwch/arduino_core_ch32#Submit-bugs)<br>

## Introduction

This repo adds the support of CH32 MCU in Arduino IDE.<br>

The file includes:
* [Arduino_Core_CH32](https://github.com/openwch/arduino_core_ch32):Public library files.
* [openocd](https://github.com/openwch/openocd_wch):can directly use WCH-LINKE to download and debug wch chips.
* [riscv-none-embed-gcc](https://github.com/openwch/risc-none-embed-gcc):A toolchain that supports WCH custom half word and byte compression instruction extensions and hardware stack push/pop functions.

## How to use

You can add this software package directly on the IDE through the [Arduino Boards Manager](https://www.arduino.cc/en/guide/cores).

Add the following link in the "*Additional Boards Managers URLs*" field:

https://github.com/openwch/board_manager_files/raw/main/package_ch32v_index.json

Then you can search for "**wch**" through the "**board manager**", find the installation package, and install it.

## Supported boards

It will be a long-term support and maintenance project, unless we encounter force majeure factors.The current version supports the following development boards:

- [CH32V00x EVT Boards](#CH32V00x-EVT-Boards)
- [CH32V20x EVT Boards](#CH32V20x-EVT-Boards)

### CH32V00x EVT Boards

| Status | Boards name | Peripherals | Release |
| :----: |     ----    |     ----    | :-----: |
| :heavy_check_mark: | CH32V003F4P | ADC,DAC,USART,GPIO,EXTI,SysTick | 1.0.0 |  

### CH32V20x EVT Boards

| Status | Boards name | Peripherals | Release |
| :----: |     ----    |     ----    | :-----: |
| :heavy_check_mark: | CH32V203G8U | ADC,DAC,USART,GPIO,EXTI,SysTick | 1.0.0 |  

## Submit bugs

If you have any questions, you could contact me through the email "*yy@wch.cn*".
Or you could [file an issue on GitHub](https://github.com/openwch/arduino_core_ch32/issues/new).


