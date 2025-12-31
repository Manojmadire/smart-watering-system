# Smart Watering System with IoT 

The Smart Watering System with IoT is an intelligent and sustainable solution designed to optimize water usage in plant irrigation. The system continuously monitors key environmental parameters such as soil moisture, temperature, humidity, and light intensity using sensors connected to a Raspberry Pi.

Based on real-time sensor data, a machine learning–based neural network model predicts the optimal duration for activating the water pump. This ensures that plants receive the right amount of water at the right time, avoiding both overwatering and underwatering.

All sensor data and model predictions are uploaded to ThingSpeak, where MATLAB is used for visualization, analysis, and automated alerts.

This project was developed as part of the MathWorks Sustainability and Renewable Energy Challenge, focusing on smart agriculture and efficient resource utilization.
# System Workflow

Sensors collect real-time environmental data.

Analog soil moisture data is converted using an MCP3008 ADC.

Raspberry Pi reads sensor values and sends data to ThingSpeak.

A trained neural network predicts valve activation duration.

MATLAB scripts analyze data, generate plots, and trigger alerts.

Camera images are uploaded to Dropbox and merged into a plant growth time-lapse

# Hardware Components
Raspberry Pi 4 Model B
Sensors
Capacitive Soil Moisture Sensor (v1.2)
DHT22 Temperature and Humidity Sensor
BH1750 Light Intensity Sensor
Actuators
Water Pump
2-Channel 5V Relay Module
Camera
Raspberry Pi Camera Module 3 NoIR
Additional Components
Breadboard
Jumper wires
MCP3008 ADC
Ethernet connection
Soil and cress seeds for testing
