# Real World Case Study

## Environment

- Bedroom on the north side of an older house
- Infrared heater
- Home Assistant
- Moes TS0201 temperature sensor (0.1 °C resolution)
- Aqara Smart Plug H2 EU

## Problem

The infrared heater produced noticeable clicking sounds caused by
thermal expansion and contraction during frequent ON/OFF cycles.

This became especially noticeable during night-time operation.

## Solution

A custom Home Assistant automation with smart hysteresis was developed.

The system uses a high-resolution 0.1 °C temperature sensor and
carefully tuned ON/OFF thresholds to reduce unnecessary switching.

## Result

- More stable room temperature
- Fewer heater switching cycles
- Reduced clicking noise
- Improved sleeping comfort
