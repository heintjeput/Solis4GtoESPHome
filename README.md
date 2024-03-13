# Solis4GtoESPHome
A Solis 4G invertor readout to ESPHome

This is a repository to document the ESP32-C3 configuration to load data from an Solis 4G inverter into ESPhome.
A large part of the idea came from the topic on Gathering of Tweakers: https://gathering.tweakers.net/forum/list_messages/1900048 . 

Included are an ESPHome yaml file, mqtt file for OTA updates and the schematic as used in EasyEDA.

The housing and connector to the inverter are used from the original WiFi / 3G data logging stick: https://nl-zonnepanelen.nl/wp-content/uploads/2020/11/Data_Logging_Stick_en_20181110-2.pdf

![Schematic_Solis4G-readout_2024-03-13](https://github.com/heintjeput/Solis4GtoESPHome/assets/18646959/60caa713-d68e-47db-82e9-05f239636b37)

For a future version I would replace the AHT21 sensor with a Sensirion SHTxx sensor as these are much better.
