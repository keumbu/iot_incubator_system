# Smart Incubator

An Arduino-based smart incubator system that monitors and controls temperature and humidity to create the ideal environment for egg incubation. It uses sensors, relays, LEDs, and a buzzer to simulate heating and cooling, along with alarm functionality.

## Features

- DHT22 sensor for temperature and humidity
- Red LED as heating element
- Blue LED as fan
- Buzzer alarm for temperature limits
- LCD display (I2C) for live temperature and humidity
- Relay control for fan and heater simulation

## Components Used

- Arduino Uno
- DHT22 sensor
- 2 Relays
- Red LED (heater)
- Blue LED (fan)
- Buzzer
- 16x2 LCD with I2C module
- Resistors (for LEDs and pull-up)
- LM7805 with capacitors (for stable 5V supply)

## Future Plans

- Wi-Fi remote monitoring with ESP8266
- Mobile control via Arduino IoT Cloud
- Real heating element and fan integration
- Humidity control with mist module


