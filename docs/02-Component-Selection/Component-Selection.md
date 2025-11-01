---
title: Component Selection 
---

**Description**

This section compares and selects key parts used in the soil moisture subsystem. Each component was chosen based on performance, compatibility with the circuit, cost, and ease of integration. The final selections provide accurate sensing and reliable operation while keeping the design simple and efficient.

*Table 1: Soil Moisture Component Options

**Soil Moisture Sensor (Subsystem)**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](op1sen.png)<br>Option 1.<br> DFRobot Capacitive Soil Moisture Sensor v1.2 (Analog)<br>$10/each<br>[link to product](https://www.dfrobot.com/product-1385.html)                 | \* Capacitive design resists corrosion better <br>\* Simple analog voltage output compatible with microcontroller ADCs <br>\* Wide community support, documentation, and example circuits                                               | \* Analog signal can fluctuate with noise <br>\* Cable length can introduce noise without shielding <br>\* Not fully waterproof out of the box |
| ![](opsen2.png)<br>\* Option 2. <br>\* Adafruit STEMMA Soil Sensor (Digital Capacitive) <br>\* $7.50/each <br>\* [Link to product](https://www.adafruit.com/product/4026) | \* Provides digital I²C output, reducing analog noise <br>\* Built in temperature sensing for compensation <br> \* Easy connection via STEMMA system | * Requires I²C communication setup and address management <br>\* Needs level shifting if using a 5 V microcontroller <br>\* Higher cost compared to analog sensors                                                          |
| ![](op3.png)<br>Option 3.<br> SunFounder Capacitive Soil Moisture Sensor Module<br>$7/each<br>[link to product](https://www.sunfounder.com/products/capacitive-soil-moisture-sensor-module?variant=44245636677867&country=US&currency=USD&utm_source=chatgpt.com)                 | \* Capacitive design (better durability vs resistive probes)<br>\* compatible with most microcontrollers<br>\* Analog output, so it plugs into ADC input easily                                                | \* Output may suffer from noise, especially with long wires <br>\* CNot completely waterproof unless sealed <br>\* Needs calibration per soil type and environment |

**Rationale** 

The Sunfounder capacitive soil moisture sensor option 3 was chosen because it is simple, reliable, and works well with our system.

* Uses an analog signal that connects directly to the microcontroller’s ADC.

* Has a corrosion resistant design for better durability and long-term use.

* Works with our 5 V power supply.

* Easy to set up, affordable, and well supported with documentation.
