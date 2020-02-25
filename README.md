# pelican
A simple wrapper to send and receive CAN frames with micropython board and MCP2515.

![Logo](doc/logo.jpg)

## Getting started
First of all it is required to connect the MCP module to the ESP32.
|MCP2515    |ESP32      |
|-----      |-----      |
|VCC        |VIN        |
|GND        |GND        |
|CS         |D27        |
|MISO       |D12        |
|MOSI       |D13        |
|SCK        |D14        |
|INT        |D26        |

