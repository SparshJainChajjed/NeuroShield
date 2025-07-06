# NeuroShield

NeuroShield is a simple Arduino-based prototype that demonstrates basic helmet detection and fall detection for motorcycle safety. The sketch controls a relay to disable the vehicle ignition unless a helmet is detected and can automatically place an emergency call in the event of a crash.

## Features

- **Helmet detection** using a capacitive sensor. If the helmet is not worn the relay disables the vehicle ignition.
- **Fall detection** via an MPU6050 accelerometer/gyroscope. When a large acceleration is detected an emergency call is placed using the SIM800 module.
- **Emergency call** logic configured for `911` by default. Adjust the phone number in the code for your region.

## Achievements

- Top 10 at CodePi 2025
- Winner of ByteBash


## Notes

This repository only contains a single example sketch. It is provided as a starting point for building a more complete motorcycle safety system.
