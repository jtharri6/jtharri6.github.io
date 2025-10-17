---
title: Component Selection 
---

**Description**

*Table 1: Soil Moisture Component Options

**Soil Moisture Sensor (Subsystem)**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](op1sen.png)<br>Option 1.<br> DFRobot Capacitive Soil Moisture Sensor v1.2 (Analog)<br>$10/each<br>[link to product](https://www.dfrobot.com/product-1385.html)                 | \* Capacitive design resists corrosion better <br>\* Simple analog voltage output compatible with microcontroller ADCs <br>\* Wide community support, documentation, and example circuits                                               | \* Analog signal can fluctuate with noise <br>\* Cable length can introduce noise without shielding <br>\* Not fully waterproof out of the box |
| ![](opsen2.png)<br>\* Option 2. <br>\* Adafruit STEMMA Soil Sensor (Digital Capacitive) <br>\* $7.50/each <br>\* [Link to product](https://www.adafruit.com/product/4026) | \* Provides digital I²C output, reducing analog noise <br>\* Built in temperature sensing for compensation <br> \* Easy connection via STEMMA system | * Requires I²C communication setup and address management <br>\* Needs level shifting if using a 5 V microcontroller <br>\* Higher cost compared to analog sensors                                                          |
| ![](op1sen.png)<br>Option 3.<br> SunFounder Capacitive Soil Moisture Sensor Module<br>$7/each<br>[link to product](https://www.sunfounder.com/products/capacitive-soil-moisture-sensor-module?variant=44245636677867&country=US&currency=USD&utm_source=chatgpt.com)                 | \* Capacitive design (better durability vs resistive probes)<br>\* compatible with most microcontrollers<br>\* Analog output, so it plugs into ADC input easily                                                | \* Output may suffer from noise, especially with long wires <br>\* CNot completely waterproof unless sealed <br>\* Needs calibration per soil type and environment |

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
