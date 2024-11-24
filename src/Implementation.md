# Implementations
The Plantos Project will be driven by a two-part prototype:
1. Product Package - Wireless sensor used to collect environmental data, connected to a mobile application that provides insights to plant health and care
2. Media Package - Documentary focused on the process of creating the sensor/app, explaining reasons of thought, struggles, success along the process.

## Product Package
The Product package is comprised of three components
1. IoT sensor
2. Mobile application
3. Timeseries ML Model

#### IoT Sensor
###### Hardware
The sensor is built of out of a RaspberryPi Pico microcontroller connected to:
- Adafruit STEMMA Soil Sensor - I2C Capacitive Moisture Sensor
- Waterproof 1-Wire DS18B20 Digital temperature sensor
- Strain Gauge Load Cell - 4 Wires - 1Kg

NEEDS TO BE OUTLINED
- [ ] waterproofing
- [ ] power
###### Software
The sensor is programmed to run a python script for network connection, collecting sensor inputs, and triggering API calls. 

## Media Package
