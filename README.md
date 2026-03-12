![Platform](https://img.shields.io/badge/platform-ESP32-blue)
![Language](https://img.shields.io/badge/language-C++-orange)
![Type](https://img.shields.io/badge/project-IoT-green)
# esp32-device-monitor
ESP32-based Wi-Fi access point that detects and logs connected devices in real time and displays them on a simple web dashboard for educational IoT networking experiments.
## Project Overview
This project demonstrates how an ESP32 can function as a Wi-Fi Access Point that monitors and logs connected devices. When a device connects to the ESP32 network, the system detects the connection event and records the device's MAC address.

The ESP32 also runs a lightweight web server that provides a simple dashboard where connected devices can be viewed in real time. This project is designed for educational purposes to explore embedded networking, IoT systems, and Wi-Fi device management.

It highlights how embedded systems can interact with network clients, process connection events, and expose device information through a browser interface.

The project requires only a single ESP32 board and demonstrates several important concepts including Wi-Fi Access Point mode, event-based device detection, and web-based monitoring.
## Features
* Creates a Wi-Fi Access Point using ESP32
* Detects devices when they connect to the network
* Logs device MAC addresses in the serial monitor
* Displays connected devices on a web dashboard
* Lightweight implementation with no external hardware required

## Learning Outcomes
* Understanding ESP32 Wi-Fi Access Point mode
* Handling Wi-Fi connection events in embedded systems
* Implementing a lightweight HTTP web server
* Building simple IoT monitoring dashboards
