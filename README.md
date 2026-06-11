# Silent Night IR Heater Pack for Home Assistant

### Developed by Darius Kisielius

A practical Home Assistant automation package designed to reduce unnecessary infrared (IR) heater switching cycles, minimize heater clicking noise and improve sleeping comfort.

## The Problem

Many infrared heaters produce clicking and cracking sounds because metal parts expand when heated and contract when cooling down.

Frequent ON/OFF cycles can become disturbing during the night, especially in quiet bedrooms and for elderly people.

## The Solution

This project combines:

- Home Assistant
- Moes TS0201 Zigbee temperature sensor (0.1 °C resolution)
- Aqara Smart Plug H2 EU
- Smart hysteresis control
- Occupancy-based heating logic

The goal is to reduce unnecessary heater switching cycles while maintaining a comfortable room temperature.

## Key Features

- Reduced heater clicking noise
- Smart hysteresis control
- Occupancy detection support
- Night heating mode
- Stable room temperature
- Improved sleeping comfort

## Tested Hardware

### Temperature Sensor
- Moes TS0201 Zigbee Temperature & Humidity Sensor

### Smart Plug
- Aqara Smart Plug H2 EU

### Platform
- Home Assistant
- Zigbee2MQTT
- ConBee II

## Real-World Use Case

Originally developed for an elderly person's bedroom located on the colder north side of an older house.

The objective was to maintain comfort while reducing heater noise during sleep.

## Version

Current version: v1.0
