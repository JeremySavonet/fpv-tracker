# fpv-tracker
An FPV antenna tracking system

The goal of this antenna tracker is to be really simple. We don't want to use any GPS or telemetry system.
It is based on RSSI directly read on the diversity VRX.

The project will be based on a STM32 chip and will use a single servo to follow the strongest signal of the flying object.

## Mechanicals:
We will use a standard photo standoff.
Enclosure of the electronic will be 3D printed.

# Electronic:
Use a STM32 + standard servo. Lipo powered and DC-DC to power 5V peripherals.

#Software:
Use ChibiOS stack
