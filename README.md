# MQTT_Temp_Hum_Baro_Sensor

This code reads values from a combination Temperature, Humidity and Barometer
sensor board using a BME280 with an ESP8266 board, and publishes the readings using MQTT.
Borrows from various examples by Adafruit and Arduino libraries.

The sensor module used was an Adafruit BME280 I2C or SPI Temperature Humidity Pressure Sensor.
The ESP8266 module was an Adafruit HUZZAH ESP8266 breakout.

The configuration of the WiFi connection and the MQTT server are
setup by connecting to an access point the ESP8266 creates on first
startup or when forced by holding the flash button for 5 seconds or so then releasing it.
More details on how this works are
documented in the example code for the WiFIManager library at:
https://github.com/tzapu/WiFiManager

