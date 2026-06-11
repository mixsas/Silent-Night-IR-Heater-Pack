# Silent Night IR Heater Pack Roadmap

## Vision

Create a practical Home Assistant heating solution focused on:

- Quiet operation
- Reduced heater clicking noise
- Stable room temperature
- Improved sleeping comfort
- Lower energy consumption

The project was originally developed for an elderly person's bedroom located on the colder north side of an older house.

The goal was to solve a real-world problem caused by infrared heater thermal expansion and contraction noises during the night.

---

# Version 1.0

## Silent Night IR Heater Pack

Features:

- Home Assistant automation
- Moes TS0201 Zigbee temperature sensor
- 0.1 °C temperature resolution
- Aqara Smart Plug H2 EU
- Smart hysteresis control
- Reduced ON/OFF switching cycles
- Stable room temperature
- Improved sleeping comfort

Default settings:

- Target temperature: 22.0 °C
- Heater ON: 21.7 °C
- Heater OFF: 22.3 °C

---

# Version 1.1

## Occupancy Edition

Future improvements:

- Occupancy detection
- Automatic comfort mode
- Automatic eco mode

Example:

Occupied room:
- Maintain 22.0 °C

Empty room:
- Reduce temperature to 20.0 °C

Benefits:

- Reduced energy consumption
- Fewer heater switching cycles
- Increased comfort

Recommended sensors:

- Aqara FP2
- Aqara FP1E

---

# Version 1.2

## Elderly Care Edition

Special version designed for elderly people.

Additional features:

- Night comfort mode
- Temperature safety alerts
- HomePod voice notifications
- HomeKit integration
- Family monitoring support

---

# Version 2.0

## Universal Smart Heater Pack

Future support:

- Infrared heaters
- Electric radiators
- Convection heaters
- Heat panels

Additional goals:

- Blueprint support
- Easy installation
- HACS distribution

---

# Why This Project Exists

Many infrared heaters create clicking and cracking noises because metal parts expand when heated and contract when cooling.

Using a precise 0.1 °C Zigbee temperature sensor together with properly tuned hysteresis helps reduce unnecessary switching cycles and improves sleeping comfort.

This project is based on real-world experience and testing.
