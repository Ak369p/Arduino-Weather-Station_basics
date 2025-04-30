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
![a151c9ae-3027-49d5-9b35-b09e82409082](https://github.com/user-attachments/assets/ddc851c9-110f-43b0-8d31-f3114b15d60a)

## 📥 Library Installation

Install the **DHT sensor library** by Adafruit:

1. Go to **Sketch > Include Library > Manage Libraries**
2. Search for **"DHT sensor library"**
3. Install the one by **Adafruit**

Also install **Adafruit Unified Sensor Library**

## 🚀 Getting Started
![WhatsApp Image 2025-05-01 at 02 36 00_c84f6888](https://github.com/user-attachments/assets/1497d12b-bf39-493c-991f-04a4e0ed56e6)
![WhatsApp Image 2025-05-01 at 02 36 00_9549f917](https://github.com/user-attachments/assets/7ad802ba-586e-47b8-81ca-cd1d0ca83abd)
![WhatsApp Image 2025-05-01 at 02 36 00_8d03a972](https://github.com/user-attachments/assets/b3ff1b44-12ac-4b03-9994-6aa1f79d9775)
![WhatsApp Image 2025-05-01 at 02 36 01_7857f650](https://github.com/user-attachments/assets/97668445-4f99-43e1-beb1-7d2b9bbee008)
![WhatsApp Image 2025-05-01 at 02 36 01_5963a9c5](https://github.com/user-attachments/assets/830fd568-2317-469a-b7ef-046222b567bc)
![WhatsApp Image 2025-05-01 at 02 36 01_6e4d5542](https://github.com/user-attachments/assets/3fae00d7-1bbc-433d-afe0-c6dd057dcd3d)

Upload the sketch below to your Arduino Nano and open the **Serial Monitor** at **9600 baud**.

## 📄 Source Code

[weather_station.ino](./weather_station.ino)



