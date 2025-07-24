Temperature Monitoring System

A simple microcontroller-based project to monitor and display temperature in real-time using sensors like LM35 or DHT11.

Features

* Real-time temperature monitoring
* Works with LM35 or DHT11 sensor
* Display output on serial monitor or LCD
* Set temperature threshold for alerts
* Easy to build and customize

Components Required

* Arduino Uno or ESP32
* LM35 or DHT11 temperature sensor
* 16x2 LCD or OLED display (optional)
* Breadboard and jumper wires
* Resistors (if required)
* USB cable or external power supply

Working Principle

* Sensor measures the ambient temperature
* Microcontroller reads and processes sensor data
* Output is displayed on LCD or serial monitor
* Alert can be triggered if temperature exceeds threshold

 Applications

* Home temperature monitoring
* Greenhouse environment control
* Industrial temperature tracking
* Server room heat detection
* Weather station projects

 File Structure

* code/ → Arduino or ESP32 code
* docs/ → Documentation (optional)

 How to Use

* Connect the temperature sensor to the microcontroller
* Upload the code to the board using Arduino IDE
* Open the Serial Monitor or LCD to view temperature readings

 Sample Output

* Temperature: 29.5 °C
* Temperature: 30.2 °C

 Future Enhancements

* Add wireless communication (Wi-Fi or Bluetooth)
* Send data to cloud platforms (ThingSpeak, Blynk, etc.)
* Add data logging with SD card module
* Connect fan or buzzer for automatic cooling
