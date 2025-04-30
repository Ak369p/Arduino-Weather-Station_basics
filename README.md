weather-station-arduino/
├── README.md
└── weather_station.ino

# 🌦️ Arduino Weather Station Using DHT11/DHT22

This is a simple weather station project built using an **Arduino Nano** and a **DHT11/DHT22** sensor. It reads the **temperature and humidity** every 2 seconds and displays the values on the **Serial Monitor**.

## 📷 Demo Output


## 🔧 Components Used

- Arduino Nano
- DHT11 or DHT22 Sensor
- Jumper Wires
- Breadboard or PCB

## 📌 Circuit Diagram

| DHT Pin | Connects To       |
|---------|-------------------|
| VCC     | 5V on Arduino     |
| GND     | GND on Arduino    |
| OUT     | D2 on Arduino     |

> **Note:** Use a 10K pull-up resistor between VCC and OUT for better stability.

## 📄 Code Explanation

The Arduino sketch reads temperature and humidity using the `DHT` library and prints the data to the Serial Monitor every 2 seconds.

## 📥 Library Installation

Install the **DHT sensor library** by Adafruit:

1. Go to **Sketch > Include Library > Manage Libraries**
2. Search for **"DHT sensor library"**
3. Install the one by **Adafruit**

Also install **Adafruit Unified Sensor Library**

## 🚀 Getting Started

Upload the sketch below to your Arduino Nano and open the **Serial Monitor** at **9600 baud**.

## 📄 Source Code

[weather_station.ino](./weather_station.ino)

