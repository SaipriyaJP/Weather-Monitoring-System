# Weather-Monitoring-System

## OVERVIEW
Our parents and grandparents were much healthier compared to us in our age. They used to breathe pure oxygen around them as the air was clear and there was no worry in inhaling polluted air. But, as of today, our generation is facing a lot of natural changes that only degrades our health. Major cause is population increase so is the degrading of the nature. This ultimately lead to climatic and weather change. There has always been a need to know the exact weather changes so as to take precautionary steps in case major natural calamities. So with the advancements in technology, it has become easier to know the change in climate and we have come up with a system that predicts the exact weather changes and this helps us in a major way. Our idea is we are using temperature and humidity sensor that can sense the temperature and humidity of the atmosphere. And also we are using pressure sensor and rainfall sensor that can sense the pressure and rainfall of the atmosphere. DTH11 sensor consists of a capacitive humidity sensing element and a thermistor for sensing temperature. Pressure sensor is made up of a semiconducting material (usually silicon) that changes resistance when a mechanical force like atmospheric pressure is applied. These sensors are connected with NodeMCU board and also connected with thinkspeak web page. Temperature, humidity, pressure and rainfall of the atmosphere is sensed by sensors and the output is shown as graph in web page.

### Components
#### NODEMCU:
It is a IOT module based on ESP8266 wifi module. Open source IOT Platform. Easily Programmable.
#### DTH11 SENSOR:
It is a low-cost digital sensor for sensing temperature andhumidity. It can be easily interfaced with any micro-controller such as Arduino, Raspberry pi, NodeMCU etc...To measure the surrounding air this sensor uses a thermistor and a capacitive humidity sensor.
#### BMP180 SENSOR:
It is designed to measure Barometric Pressure or Atmospheric Pressure. It senses the pressure and provides that information in digital outputs.
#### RAIN SENSOR:
It is used to notice the water drops or rainfall. This sensor includes two parts like sensing pad and a sensor module. Whenever rain falls on the surface of a sensing pad thenthe sensor module reads the data from the sensor pad to process and convert it into an analog or digital output.

### Working
Nodemcu is placed in the breadboard.VIN is connected to positive nodemcu and GND is connected to the negative nodemcu.DHT11 sensor is placed in the breadboard where the positive of DHT11 is connected to the VIN of nodemcu and the output of DHT11 is connected to D3 of nodemcu and negative of DHT11 is connected to GND of nodemcu. BMP180 sensor is placed in the breadboard where VCC of BMP180 sensor is connected to VIN of nodemcu and GND of BMP180 is connected to GND of nodemcu and SCL of BMP180 is connected to D1 of nodemcu and SDA of BMP180 is connected to D2 of nodemcu. Rain sensor is placed in the breadboard where AO of rain sensor is connected to AO of nodemcu and GND of rain sensor is connected to GND of nodemcu and VCC of rain sensor is connected to VIN of nodemcu.

### Conclusion
Weather monitoring system provides an efficient and safe system for detecting agricultural parameters. The results of weather can be seen as graph in the web page. IOT-Based weather monitor calculating system provides an efficient and safe system for detecting agricultural parameters. Our System enables the environment to be self-protected by having the sensors integrated in the monitoring environment. To implement this, sensors need to be installed to capture and interpret data in the particular area. With the Internet of Things theory, which is experimentally tested to control the parameters, which are temperature, humidity, pressure and rainfall can be monitored.
