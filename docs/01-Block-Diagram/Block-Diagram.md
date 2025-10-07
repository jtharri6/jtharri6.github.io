---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview

This block diagram outlines my soil moisture sensing subsystem and how it connects to our team’s plant project. The subsystem operates from a regulated 5 V rail powering the sensor, op-amp, and MCU. A capacitive moisture sensor feeds a single-supply, non-inverting op-amp, and the conditioned voltage is sampled by the MCU, ADC on RA0. For team integration, RA1 is wired to Connector 1 (pin 1) which is a digital parallel line, and PWM on RB2 is reserved for a future water pump.

## Block Diagram 

![BlockDiagram](docs/01-Block-Diagram/ibd.png)
