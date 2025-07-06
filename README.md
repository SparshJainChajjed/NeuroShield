# NeuroShield

NeuroShield is a simple prototype that demonstrates basic helmet detection and fall detection for motorcycle safety. The software controls a relay to disable the vehicle ignition unless a helmet is detected and can automatically place an emergency call in the event of a crash.

## Problem statement

Motorcycle riders are highly vulnerable in traffic crashes. The World Health Organization reports that wearing a helmet reduces the risk of fatal injury by around 40% and the risk of serious head injury by over 70%. In 2023, the U.S. National Highway Traffic Safety Administration recorded more than 5,000 motorcycle fatalities. NeuroShield aims to mitigate these risks by enforcing helmet use and providing rapid emergency notifications after a collision.

## Features

- **Helmet detection** using a capacitive sensor. If the helmet is not worn the relay disables the vehicle ignition.
- **Fall detection** via an MPU6050 accelerometer/gyroscope. When a large acceleration is detected an emergency call is placed using the SIM800 module.
- **Emergency call** logic configured for `911` by default. Adjust the phone number in the code for your region.

## Achievements

- Top 10 at CodePi 2025
- Winner of ByteBash

