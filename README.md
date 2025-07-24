Temperature Monitoring System

This project is designed to continuously monitor the surrounding temperature using a sensor connected to a microcontroller. The temperature is displayed in real-time and alerts can be triggered if it exceeds a set threshold.

Features

Real-time temperature monitoring

Displays temperature on LCD or Serial Monitor

Customizable alert threshold

Low power and simple hardware

Can be upgraded for IoT or remote monitoring

Hardware Required

Arduino Uno / ESP32 / Raspberry Pi

Temperature Sensor (LM35 / DHT11 / DS18B20)

16x2 LCD display or use Serial Monitor

Breadboard and jumper wires

USB cable or battery pack

Software Required

Arduino IDE

Required libraries based on sensor:

LiquidCrystal (for LCD)

DHT / OneWire + DallasTemperature (for sensor)

How to Use

Connect the temperature sensor to the microcontroller.

Upload the code using Arduino IDE.

Open Serial Monitor or view LCD to see temperature data.

Set a threshold in the code to activate alerts if temperature gets too high.

How It Works

The sensor reads the temperature.

The microcontroller processes the data.

Output is displayed on screen or monitor.

If the temperature is above the limit, an LED, buzzer, or message can alert the user.

Future Improvements

Add data logging to SD card

Connect to Wi-Fi for remote access

Send alerts via SMS or mobile apps

Display temperature charts on cloud dashboard

