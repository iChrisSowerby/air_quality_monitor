# air_quality_monitor

[![GitHub release](https://img.shields.io/github/v/release/adamHassanBR/air-quality-sensor)](https://github.com/adamHassanBR/air-quality-sensor/releases)

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC--BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

[Maker World - Air Quality Monitor by Chris3D](https://makerworld.com/en/models/1977297-air-quality-sensor-esphome-for-home-assistant#profileId-2126773)

# Description

## 🌿 Air Quality Monitor (ESP32-S3 + ESPHome + Home Assistant)

This custom Air Quality Monitor is a smart home project built around the ESP32-S3, designed to help you monitor and optimise the air quality in your home. It runs fully on ESPHome, seamlessly integrating with Home Assistant for real-time data, automation, and visual feedback.

## 🧠 What It Does

The monitor continuously measures:

🌫️ Particulate Matter (PM1.0, PM2.5, PM10) via a PMS sensor

💨 CO₂ and TVOC levels from a CCS811 sensor

🌡️ Temperature, Humidity, and Pressure from a BME680

☀️ Ambient Light levels from a VEML7700

All readings are displayed on a high-contrast OLED screen and also sent to Home Assistant for automation and long-term tracking.

## 💡 Dynamic RGB LED Feedback

An integrated WS2812 RGB LED provides an at-a-glance visual indicator of air quality:

🟩 Excellent: Clean air, light green

🟢 Good: Healthy environment, soft green

🟡 Moderate: Acceptable but can be improved, yellow-orange tone

🟥 Poor: Consider ventilation, red

🟣 Unhealthy: Take action to clean the air, purple

## 🌈 Optional: 3D Printed Light Diffuser

To achieve a softer and more visually pleasing glow, the LED can be positioned behind a 3D printed light diffuser.
This diffuser helps blur the individual LEDs, spreading the light evenly and giving a professional, polished look to the device.
It’s especially effective for night-time use, ensuring the indicator remains visible without being harsh or distracting.

## 🖥️ Customisable OLED Display

The OLED screen is fully configurable - show live sensor data, weather information, forecasts, or time.
(Note: the photos show light streaks on the display - that’s only due to the camera refresh rate; in person, the screen is perfectly clear.)

## ⚙️ Hardware & Build

The compact enclosure is 3D printed and designed to hold each component neatly in place:

Slots for each module (sensors, and display)

Components are easily secured using hot glue

Printed in Marble PLA with a Grey PLA lid - but feel free to print in any material or colour combination you like

⚠️ Tip: Leave enough wire between components to make soldering and installation easier. The build takes a bit of patience and careful soldering, but it’s entirely achievable even for hobbyists.

## 🏡 Why Build It?

If you care about indoor comfort, allergies, or just want a smarter home environment, this monitor helps you understand and improve your indoor air quality - ensuring you and your family always breathe clean air.

## 🔧 Technical Details

Microcontroller: ESP32-S3-DevKitC-1

Firmware: ESPHome (Home Assistant integrated)

Display: 128x64 OLED (SSD1306)

Lighting: WS2812 addressable LED

Sensors: BME680, CCS811, PMSX003, VEML7700

# Dimensions

![Diagram](https://makerworld.bblmw.com/makerworld/model/DSM00000001977297/design/2025-11-09_e9e1b4e07944c8.png?x-oss-process=image/format,webp)

# Materials:

- ESP32 S3 DevKitC 1 N16R8 (other ESP devices should work, providing they accept 5V input via one of the pins instead of the USB port)
- VEML7700 (Light Sensor)
- WS2812B LED Strip (total of 5 leds)
- PMS5003 (Particulate Matter Readings)
- CCS811 (CO2/TVOC Sensor)
- BME680 (Temperature/Humidity/Pressure/VOC Gas)
- OLED 0.96" (128X64)
- USB C Female Plug
- Soldering Iron
- Glue Gun
- 3D Printer
- 4-6 colours of wires
