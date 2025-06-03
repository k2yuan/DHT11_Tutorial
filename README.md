# DHT11 with ESP32 DevBoard

## Introduction
This tutorial will guide you through interfacing a DHT11 temperature and humidity sensor with an ESP32 DevBoard. You’ll learn how to wire the sensor, install the necessary library, and upload test code to Arduino.

The DHT11 is a low-cost digital sensor for measuring temperature and humidity. When paired with an ESP32 DevBoard, it can feed real-time environmental data into your sensor projects. By the end of this tutorial, you’ll be able to:

- Read temperature (°C and °F) and humidity (%) from a DHT11 sensor  
- Display readings via the Serial Monitor

---

## Materials Needed

- **ESP32 DevBoard**
- **DHT11 Sensor Module** (with 3 pins: VCC, GND, Data)  
- **Male-to-Female Jumper Wires** (3×)  
- **Computer** with Arduino IDE installed

## Instruction

- Connect the left pin to PIN 21
- Connect the middle pin to 3.3V
- Connect the right pin to GND

As illustrated in this picture:


## Installing the DHT Library

1. Open the Arduino IDE.  
2. Go to **Sketch** → **Include Library** → **Manage Libraries…**  
3. In the Library Manager, search for **“DHT sensor library”** by Adafruit. Click **Install**.  
4. Also search for **“Adafruit Unified Sensor”** (dependency) and click **Install**.
