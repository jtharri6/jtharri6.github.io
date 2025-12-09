---
title: Hardware V2.0
---

For version 2 of my soil sensor, I would still use copper tubing for the probe but add a few small improvements to make the readings more consistent.

### Probe Improvements
- Use thinner and shorter copper tubing for easier soil insertion.
- Adjust spacing between the rods for more stable readings.
- Seal the wire connections to protect them from moisture.

### PCB Improvements
- Shorten analog traces to reduce noise.
- Use a more efficient voltage regulator.
- Reorganize the PCB layout so sensor parts and test points are easier to reach.

## Lessons Learned & Recommendations for Future Students
- Sensor probe matters with material and also designing such as rod spacing and length which can affect the readings.
- Op amp performance is very sensitive to resistor values and has to make sure it is set up right either buffering or amplifying a signal.
- Adding test points and LEDs early makes debugging easier.
- UART output can be tricky to set up correctly so make sure to reread which pins work and read datasheets.
- Calibrating wet and dry values can be a pain.
- Breadboard and PCB version of a system don’t always behave the same.
- Double check footprints on all components and measure if needed.
- Datasheets are your friend.













