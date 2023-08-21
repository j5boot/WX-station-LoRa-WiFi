# WX-station-LoRa-WiFi
An APRS LoRa weather station with a TTGO T3 module.

This is the description of a Weather station build with a TTGO T3 module that can :
- measure pressure, temperature, humidity, wind speed, wind direction, wind gust speed & direction, rain fall.
- transmit datas to APRS in LoRa, APRS-IS, Wunderground & MQTT via WiFi.
- display datas on the OLED screen.
- display a Web page server with data display.
- upgrade via OTA.

The pressure, temperature & humidity are measured with a BME280 multi-sensor on the i2C bus.
The wind direction and speed are measured in ModBus mode via RS485, allowing long distance measurements.
The rain fall is measured with a rain bucket gauge.

![wx-station-screen1](https://github.com/tk5ep/WX-station-LoRa-WiFi/assets/1655173/b155929d-1387-497c-858d-efabd9410c22)
