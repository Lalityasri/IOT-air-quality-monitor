# IOT-air-quality-monitor


## Project overview
The IoT Air Quality Monitoring System is designed to continuously monitor air quality using gas and environmental sensors, providing real-time data to users via a cloud platform. This system enables individuals and authorities to track pollution levels and take timely actions to improve environmental health.

Using microcontrollers like NodeMCU and sensors such as MQ-135, the system collects data on pollutants like CO₂, NH₃, and smoke. The data is then transmitted over Wi-Fi to an IoT platform like Blynk, Thingspeak, or Firebase, where users can remotely monitor and analyze trends.


## Components and apps used
Hardware Components:
NodeMCU ESP8266 – Microcontroller with built-in Wi-Fi for data transmission

MQ-135 Gas Sensor – Detects CO₂, NH₃, Benzene, and other harmful gases

DHT11 / DHT22 Sensor – Measures temperature and humidity (optional but useful)

OLED Display (optional) – For displaying local sensor readings

Breadboard and Jumper Wires

Power Supply / USB cable
Software & Cloud Tools:
Arduino IDE – For writing and uploading code to NodeMCU

Blynk App / Thingspeak / Firebase – Cloud platforms for remote data visualization

GitHub – Version control and project documentation


## Libraries used for compiling the code
The following libraries are essential to compile and upload the firmware:

ESP8266WiFi.h – Enables Wi-Fi functionality

BlynkSimpleEsp8266.h – For Blynk cloud communication

Adafruit_Sensor.h – Required for DHT sensor

DHT.h – Library for DHT11/DHT22 temperature & humidity sensor

MQUnifiedsensor.h (optional) – For accurate MQ-series gas sensor readings

These libraries can be installed via the Arduino Library Manager or imported manually from GitHub.


## Project outcome
Upon successful completion, the system is able to:

Monitor gas levels and environmental conditions in real time

Send sensor data to a cloud dashboard at regular intervals

Alert users via mobile app if gas concentration crosses a defined threshold

Display live readings on a mobile app or OLED screen

Provide historical data tracking via Thingspeak or Firebase


## Conclusion
The IoT Air Quality Monitoring System is a cost-effective, scalable solution for environmental tracking. It empowers users with real-time data to assess indoor or outdoor air quality, contributing to health, safety, and awareness. This project can be expanded to support government monitoring, industrial safety, or smart city integration.
![Screenshot (52)](https://github.com/user-attachments/assets/724a6b00-6fe1-4c0b-a094-4f7957ca0c51)
