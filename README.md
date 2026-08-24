# esp32-dht-weather-station
# ESP32 DHT Weather Station

Two versions of the same temperature/humidity monitoring project:

- **dht22-wokwi/** — DHT22 sensor, simulated in [Wokwi](https://wokwi.com)
- **dht11-hardware/** — DHT11 sensor, built and tested on real ESP32 hardware

## DHT11 vs DHT22
- DHT11: cheaper, ±2°C / ±5% RH accuracy, 1Hz sampling
- DHT22: more precise, ±0.5°C / ±2% RH accuracy, 0.5Hz sampling, wider range

## Live simulation
Import `dht22-wokwi/` into wokwi.com to run it in-browser — no hardware needed.
