# Installation Guide

## Requirements

Before installation, make sure you have:

- Home Assistant
- Zigbee network
- Zigbee2MQTT
- Zigbee temperature sensor
- Smart plug connected to your heater

Recommended hardware:

- Moes TS0201 Temperature & Humidity Sensor
- Aqara Smart Plug H2 EU

---

## Step 1 - Add Devices

Add your temperature sensor and smart plug to Home Assistant.

Verify that:

- Temperature readings are visible.
- Smart plug can be turned ON and OFF from Home Assistant.

---

## Step 2 - Configure Entities

Example entities used in this project:

Temperature sensor:

sensor.tz3000_ywagc4rj_ts0201_temperatura

Smart plug:

switch.aqara_wall_outlet_h2_eu

Adjust entity names according to your installation.

---

## Step 3 - Configure Temperature Limits

Recommended values:

Target temperature: 22.0 °C

Heater ON: 21.7 °C

Heater OFF: 22.3 °C

---

## Step 4 - Test Operation

Verify that:

- Heater turns ON below 21.7 °C
- Heater turns OFF above 22.3 °C
- Temperature remains stable

---

## Step 5 - Fine Tune Hysteresis

Adjust hysteresis values according to:

- Room size
- Heater power
- Building insulation
- Personal comfort preferences

---

## Why This Works

Infrared heaters often produce clicking sounds caused by thermal expansion and contraction of metal components.

Using a precise 0.1 °C Zigbee temperature sensor and properly tuned hysteresis helps reduce unnecessary switching cycles and improve sleeping comfort.

---

## Tested Environment

- Home Assistant
- Zigbee2MQTT
- ConBee II
- Moes TS0201
- Aqara Smart Plug H2 EU
