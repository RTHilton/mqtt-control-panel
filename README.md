# mqtt-control-panel

A simple alarm control panel for Home Assistant's `manual_mqtt` alarm. Designed to run on a Raspberry Pi using an Adafruit 3.5" PiTFT.

![](screenshot.png)

# Hardware

 - Raspberry Pi Zero Wireless (other modern Pis will likely work fine)
 - Adafruit PiTFT 3.5" display

# Requirements

This project requires Python 2.7 with the following packages:

 - paho-mqtt
 - pygame
 - python-dotenv

# Configuration

Copy `.env.dist` to `.env` and update the values accordingly.