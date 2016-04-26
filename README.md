# wundergroundBlynk
<p align="center"><img src="http://i.imgur.com/bLBpyt9.png"/></p>
This is a relatively simple method to get weather data (simply the current temperature in fahrenheit, in this case) and plug it into a variable in my Arduino sketch. This sketch lives on an ESP-8266 (ESP-01), but I did my initial testing on an Arduino Uno R3.

## Libraries and Resources

Title | Include | Link
------|---------|------
SimpleTimer | SimpleTimer.h | https://github.com/jfturcot/SimpleTimer
ESP8266/Arduino | ESP8266WiFi.h | https://github.com/esp8266/Arduino
blynk-library | BlynkSimpleEsp8266.h, WidgetRTC.h | https://github.com/blynkkk/blynk-library
ArduinoJson | ArduinoJson.h | https://github.com/bblanchon/ArduinoJson
ESP8266 board mgr | N/A | [json](http://arduino.esp8266.com/stable/package_esp8266com_index.json) & [instructions](https://github.com/esp8266/Arduino#installing-with-boards-manager)

All the credit and the biggest thanks to bbx10node@gmail.com (https://github.com/bbx10/esp-pcd-weather.git) for the horsepower to make this work. [How to edit this.](https://guides.github.com/features/mastering-markdown/)

Wunderground, Weather Underground, and all the respective logos, etc., are © Copyright The Weather Company, LLC
