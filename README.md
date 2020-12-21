# ArduinoEnvMonitoring
Arduino based environment monitoring with observer programming pattern.

## How does it work

Read data from the sensor -> Update the display -> Wait -> Start again

### Okay, but how?

1. Create a subject 
2. Subscribe to the subject with an observer
3. Update the subscribers in every cycle

## Hardware

- Arduino Nano v3.0
- TM1637 7-segment 4-digit display
- DHT11 Temperature & Humidity Sensor
- Jumper wires (generic)
- Breadboard (generic)
- Arduino USB 2.0 Cable

## Used libraries

- DHT11: 
*https://github.com/adafruit/DHT-sensor-library*

- TM1637: 
*https://github.com/bremme/arduino-tm1637*

- Implemented design pattern: 
*https://refactoring.guru/design-patterns/observer/cpp/example*

## Development environment

- Arduino IDE 1.8.13
- Windows 10
- Arduino Nano V3.0
