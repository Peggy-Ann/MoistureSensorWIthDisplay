# Moisture Sensor With Display
Esphome based moisture sensor with display

Code is written for a analogue moisture sensor, an Arduino mini D1 and a 128x64 pixels display.
The WiFi connection parameters are in the wifi_example file and needs to be updated with correct settings.
If you wish to use MQTT then those parameters also needs to be configuered in the mqtt_example file.
Both mqtt_example and wifi_example needs to be renamed(or new files added) without the "_example".
MQTT is not needed for this to work since it also shows information on the display.
