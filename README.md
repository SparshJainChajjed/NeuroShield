# NeuroShield

NeuroShield is a simple Arduino-based prototype that demonstrates basic helmet detection and fall detection for motorcycle safety. The sketch controls a relay to disable the vehicle ignition unless a helmet is detected and can automatically place an emergency call in the event of a crash.

## Features

- **Helmet detection** using a capacitive sensor. If the helmet is not worn the relay disables the vehicle ignition.
- **Fall detection** via an MPU6050 accelerometer/gyroscope. When a large acceleration is detected an emergency call is placed using the SIM800 module.
- **Emergency call** logic configured for `911` by default. Adjust the phone number in the code for your region.

## Getting started

1. Open the `code` file in the Arduino IDE. You may rename it to `NeuroShield.ino` if preferred.
2. Install the required libraries:
   - `MPU6050` library
   - `SoftwareSerial` (usually included with the Arduino core)
3. Connect the hardware:
   - MPU6050 sensor to the I2C pins
   - Capacitive helmet sensor to digital pin 2
   - Relay to digital pin 4
   - SIM800 module to pins 10 (RX) and 11 (TX)
4. Upload the sketch to your Arduino-compatible board.

## Notes

This repository only contains a single example sketch. It is provided as a starting point for building a more complete motorcycle safety system.
