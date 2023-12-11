#### Hi, I'm Stefan Tobiasiewicz and this is a short description of some of my projects that I have done in the last two years


## Soil Sensor:

Device desinged to monitor soil moisture of plant. Project finally baser on NRF52833 SoC. In
previous version was based on NRF52811. Device use capacitive soil sensor. During development my own
design of this type sensor was created. Device use NRF52833 SoC for future work in Zigbee network.
Currently device use BLE for sending data to software. Also to this project I wrote python
application listening advertisement form devices and pushes it to mqtt broker. Device is powered by
two AAA batteries. All versions was programed using nrf Connect SDK.

I designed three versions of PCBs, and the latest one includes additional light, humidity, and
temperature sensors. However, this version has not been assembled yet.

<img alt="drawing" src="img/SoilSensor/IMG_1604.jpeg" width="600"/>

Looks of designed PCB


<img alt="drawing" src="img/SoilSensor/IMG_1605.jpeg" width="600"/>
<img alt="drawing" src="img/SoilSensor/IMG_1606.jpeg" width="600"/>

Programmer and programming station (bottom pads match proggramer pins in 3d printed case):

<img alt="drawing" src="img/SoilSensor/IMG_1607.jpeg" width="600"/>
<img alt="drawing" src="img/SoilSensor/IMG_1608.jpeg" width="600"/>

Current final working PCB

<img alt="drawing" src="img/SoilSensor/IMG_1614.jpeg" width="600"/>

## Bug Box:

Project for monitoring the bug breeding process (bugs is gecko food). The project is based on
Raspberry Pi Zero, and the main application is written in Python. The device is equipped with a
camera, temperature sensor, and humidity sensor. It captures an image every 15 minutes and reports
environmental data. The deployment process is managed through bash scripts, executed on a single
Raspberry Pi to deploy new versions of the application. All data is sent to a blob storage Minio,
which is running on another server machine.


<img alt="drawing" src="img/BugBox/IMG_1615.jpeg" width="600"/>
<img alt="drawing" src="img/BugBox/IMG_1616.jpeg" width="600"/>
<img alt="drawing" src="img/BugBox/IMG_1617.jpeg" width="600"/>
<img alt="drawing" src="img/BugBox/IMG_1618.jpeg" width="600"/>
<img alt="drawing" src="img/BugBox/IMG_1619.jpeg" width="600"/>


## Water dispenser:

Project created for watering plants. Based on NRF52820 SoC and programed using Nrf connect SDK.
Device use BLE for interact with user. Aso for project was created application in python to control
it. Device use relay valve and water flow sensor, it allows to dispense water precisely. Device use
230v-12V AC-DC converter to power up relay and main board.

<img alt="drawing" src="img/WaterDispenser/IMG_1596.jpeg" width="600"/>
<img alt="drawing" src="img/WaterDispenser/IMG_1597.jpeg" width="600"/>
<img alt="drawing" src="img/WaterDispenser/IMG_1593.jpeg" width="600"/>
<img alt="drawing" src="img/WaterDispenser/IMG_1592.jpeg" width="600"/>
<img alt="drawing" src="img/WaterDispenser/IMG_1591.jpeg" width="600"/>

## Contact Sensor:

Project which I've done to pass Beatcher engineering degree.

Device is designed to work as door/window open close sensor in Zigbee network. Device works with
Zigbee2Mqtt platform and Home Assistant software. Device is based on NRF52840 Soc from Nordic
Semiconductor and software was created using nRF5 SDK for Thread and Zigbee. PCB was designed by me
nad ordered form factory. I soldered everything using solder paste and homemade hotplate and using
iron.

<img alt="drawing" src="img/ContactSensor/IMG_1609.jpeg" width="600"/>
<img alt="drawing" src="img/ContactSensor/IMG_1610.jpeg" width="600"/>

Also I designed cover and print it on 3d print:

<img alt="drawing" src="img/ContactSensor/IMG_1611.jpeg" width="600"/>
<img alt="drawing" src="img/ContactSensor/IMG_1612.jpeg" width="600"/>
<img alt="drawing" src="img/ContactSensor/IMG_1613.jpeg" width="600"/>

## Gecko Controller:

Project designed for controlling gecko terrarium. Device control heater plate under the pet sleep
place and lighting in terrarium. Device is based on ESP-12F microcontroller. Device expose REST API
for control.

<img alt="drawing" src="img/GeckoController/IMG_1601.jpeg" width="600"/>
<img alt="drawing" src="img/GeckoController/IMG_1602.jpeg" width="600"/>
<img alt="drawing" src="img/GeckoController/IMG_1603.jpeg" width="600"/>

## Gecko Heater:

Project designed for heating air temperature in gecko terrarium. Device works like hair drier, fan
press air to the heat spiral made form resistance wire. All device based on Atmega8 and use serial
port for control. Over serial port is implemented AT command protocol parser wrote by myself. Device
take 12V form external power supply.

<img alt="drawing" src="img/GeckoHeater/IMG_1598.jpeg" width="600"/>
<img alt="drawing" src="img/GeckoHeater/IMG_1599.jpeg" width="600"/>
<img alt="drawing" src="img/GeckoHeater/IMG_1600.jpeg" width="600"/>

