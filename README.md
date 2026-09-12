# ESP32 Wi-Fi Web Server

A simple ESP32 IoT project that controls the built-in LED through a web browser over Wi-Fi.

## Features

* Connects ESP32 to Wi-Fi
* Hosts a web server on port 80
* ON/OFF LED control through browser
* Displays ESP32 IP address on Serial Monitor

## Hardware

* ESP32 Development Board
* USB Cable

## Libraries

```cpp
#include <WiFi.h>
#include <WebServer.h>
```

## How to Use

1. Enter your Wi-Fi name and password in the code.
2. Upload the code to ESP32.
3. Open Serial Monitor at **115200 baud**.
4. Copy the displayed IP address.
5. Open the IP address in a browser connected to the same Wi-Fi.
6. Use the **Turn ON** and **Turn OFF** buttons to control the LED.

**LED Pin:** GPIO 2
