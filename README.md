This repo contains my Home Assistant configuration. Home Assistant is open source home automation powered by a worldwide community of tinkerers. More information can be found at their website, https://www.home-assistant.io.

# Home Assistant

My home automation is not as advanced as many other configurations but for me it is very practical and I use it on a daily basis. The house should still be functional even when the internet or software is down. That results into solution that don't use cloud services and everything can be operated manually.  

## Current infrastructure

I'm using a Raspberry Pi 3 [Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/) configured with [Docker](https://www.docker.com/) running:
* Home Assistant Core 
* [Zigbee2MQTT](https://www.zigbee2mqtt.io/) running a Zigbee network
* [ESPHome](https://esphome.io/) for programming my ESP devices

### Connected Devices

* AZDelivery [ESP32 NodeMCU](https://www.az-delivery.de/nl/products/esp32-developmentboard) installed with ESPHome
* [Shelly 1](https://shelly.cloud/products/shelly-1-smart-home-automation-relay/)
* [Shelly Plug s](https://shelly.cloud/products/shelly-plug-s-smart-home-automation-device/)
* [slae.sh CC2652R](https://slae.sh/projects/cc2652/) stick as Zigbee Controllor
* Xiaomi MIJIA [Temperature and Humidity Monitor](https://www.google.com/search?q=MIJIA+Temperature+and+Humidity+Monitor+2) connected via BLE to ESPHome

## Lovelace setup

### Resources

I've extended the Lovelace interface with some custom plugins which are installed manually.

* [Mini Graph Card](https://github.com/kalkih/mini-graph-card) to display climate graphs like temperature & humidity.
* [Multiple Entity Row](https://github.com/benct/lovelace-multiple-entity-row) to show multiple entity states in row.



