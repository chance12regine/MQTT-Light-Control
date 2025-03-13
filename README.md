# Light Control Web Application

This project simulates a simple light control system using MQTT. The user can control a light (simulated by an ESP8266 device) through a web interface, sending MQTT messages to turn it on or off.

### How to Run:
1. Run the `light_simulation.py` script to simulate the IoT device.
2. Open `index.html` in a web browser to control the light.

### MQTT Broker:
The application uses a public MQTT broker at `broker.hivemq.com`.

### Dependencies:
- `paho-mqtt` (Python library for MQTT)
