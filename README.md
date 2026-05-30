# Arduino Temperature and Humidity Monitor

A simple Arduino project that reads temperature and humidity from a DHT11 sensor and displays the values on a 16x2 I2C LCD.

## Components

- Arduino Uno
- DHT11 Temperature & Humidity Sensor
- LCD 16x2 I2C
- Jumper Wires
- Breadboard

## Wiring

### DHT11

| DHT11 | Arduino Uno |
|--------|------------|
| VCC | 5V |
| DATA | D2 |
| GND | GND |

### LCD 16x2 I2C

| LCD I2C | Arduino Uno |
|----------|------------|
| VCC | 5V |
| GND | GND |
| SDA | A4 |
| SCL | A5 |

## Features

- Reads temperature in Celsius
- Reads humidity percentage
- Displays values on LCD 16x2 I2C
- Updates every 2 seconds

## Libraries

- LiquidCrystal_I2C
- DHT Sensor Library
- Adafruit Unified Sensor

## Example Output

Temp: 29°C
Hum : 75%

<img width="500" alt="trashed-1782734529-IMG_20260530_190200" src="https://github.com/user-attachments/assets/e9722e07-f12f-4558-befe-5f37a7015b7d" />



## Author

Duy
