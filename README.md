# Home Assistant

## Current infrastructure

I'm using a Raspberry Pi 3 [Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/) configured with [Docker](https://www.docker.com/) running:
* Home Assistant Core 
* [Zigbee2MQTT](https://www.zigbee2mqtt.io/) running a Zigbee network
* [ESPHome](https://esphome.io/) for programming my ESP devices

### Connected Devices

* AZDelivery [ESP32 NodeMCU](https://www.az-delivery.de/nl/products/esp32-developmentboard) installed with ESPHome
* [Shelly 1](https://shelly.cloud/products/shelly-1-smart-home-automation-relay/)
* [slae.sh CC2652R](https://slae.sh/projects/cc2652/) stick as Zigbee Controllor
* Xiaomi MIJIA [Temperature and Humidity Monitor](https://www.google.com/search?q=MIJIA+Temperature+and+Humidity+Monitor+2) connected via BLE to ESPHome

## Lovelace setup

### Resources
