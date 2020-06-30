# Home Assistant configuration

![home screen](https://user-images.githubusercontent.com/8268674/86159451-47f83900-bb02-11ea-9b3f-6bb5451eee77.png)

![security](https://user-images.githubusercontent.com/8268674/86175483-56068380-bb1b-11ea-9421-d7bd083613a6.png)

![admin](https://user-images.githubusercontent.com/8268674/86176680-34a69700-bb1d-11ea-850e-d82b3694eb56.png)

## Add-ons
![image](https://user-images.githubusercontent.com/8268674/86160003-12078480-bb03-11ea-88f3-d1482acd2406.png)

#### Hacs integrations
* Sonoff LAN - for camera control
* AccuWeather - since DarkSky is shutting down its API

## Devices

| Connection | Brand | Model | Photo | Notes |
|:-----|:-----|:-----|:-----|:-----|
| **WiFi** |  |  |  |  |
|  | Sonoff | S20 | ![image](https://user-images.githubusercontent.com/8268674/85944365-1464b580-b92e-11ea-90a1-0f4fa9e6546d.png) | Smart plug; ESPHome firmware
|  | Sonoff | Touch | ![image](https://user-images.githubusercontent.com/8268674/85944447-b4bada00-b92e-11ea-8411-f785e0630398.png) | Smart wall switch; ESPHome firmware
|  | Shelly | 1 | ![image](https://user-images.githubusercontent.com/8268674/85944528-4fb3b400-b92f-11ea-8444-9ad851cfa497.png) | Smart switch; ESPHome firmware
|  | Tp-Link | HS110 | ![image](https://user-images.githubusercontent.com/8268674/85944585-c486ee00-b92f-11ea-857f-745ec5a34fc4.png) | Smart plug with energy monitoring
|  | Broadlink | RM mini 3 | ![image](https://user-images.githubusercontent.com/8268674/85944713-d3ba6b80-b930-11ea-8c70-c0141ee834b8.png) | IR remote controller (not configured yet)
|  | Sonoff | GK-200MP2-B | ![image](https://user-images.githubusercontent.com/8268674/86054006-49b5f400-ba51-11ea-8d85-fa57775cf387.png) | IP camera; Pan-tilt controlled via Home Assistant
|  | D-Link | DCS-932L | ![image](https://user-images.githubusercontent.com/8268674/86054297-cea10d80-ba51-11ea-9546-643240c78b7c.png) | IP camera
| **RF433** |  |  |  | 
|  | RFXCOM | RfxTrxE | ![image](https://user-images.githubusercontent.com/8268674/86055023-183e2800-ba53-11ea-9aab-57f64a405b68.png) | USB RF transceiver
|  | OWL | OWL Intuition Gateway | ![image](https://user-images.githubusercontent.com/8268674/86055820-48d29180-ba54-11ea-9bfc-0a7a50e383f4.png) | Energy monitoring via CT (current transformer) sensor
|  | Nexa | LML-710 | ![image](https://user-images.githubusercontent.com/8268674/86056059-bb437180-ba54-11ea-9a1f-59221257fe99.png) | Doorbell
|  | Nexa | LWST-605 | ![image](https://user-images.githubusercontent.com/8268674/86056642-aca98a00-ba55-11ea-9d7d-29d0ad6ea21a.png) | Wall switch
| **ZigBee** |  |  |  |  |
|  | Phoscon | ConBee II | ![image](https://user-images.githubusercontent.com/8268674/86056863-0742e600-ba56-11ea-82e5-594602251075.png) | USB ZigBee transceiver
|  | Aqara | RTCGQ11LM | ![image](https://user-images.githubusercontent.com/8268674/86057757-aa482f80-ba57-11ea-981b-93240ea72485.png) | Human motion sensor
|  | Aqara | WSDCGQ11LM | ![image](https://user-images.githubusercontent.com/8268674/86058008-0f038a00-ba58-11ea-95a8-b475cbc66190.png) | Temperature and humidity sensor
|  | Aqara | QBKG04LM | ![image](https://user-images.githubusercontent.com/8268674/86058351-ac5ebe00-ba58-11ea-84ba-53873a70667a.png) | Smart wall switch (2 gang) connected to mains (no neutral version)
|  | Aqara | QBKG02LM  | ![image](https://user-images.githubusercontent.com/8268674/86059062-eb414380-ba59-11ea-8871-f4d97840d5b9.png) | Smart wall switch (2 gang) battery powered
|  | Aqara | MCCGQ11LM | ![image](https://user-images.githubusercontent.com/8268674/86059453-aff34480-ba5a-11ea-84e9-6eceee5e0c45.png) | Door sensor


#### Devices used in the past

| Connection | Name | Notes |
|:----|:----|:----|
| Wifi | Tp-Link HS100 | Used in the past mainly with Domoticz and I switched to Sonoff S20 in the same time when I've migrated to HA
| RF433 | Telldus TellstickNet | Both mainly for connecting with Nexa devices. It was working but just partially - RfxTrxE works much better with Nexa and other RF devices.
| RF433 | CoTech motion sensor | Battery lasts for 2-3 months. Not convenient to use as different ID sent when motion is detected and different when there is no move any more
| RF433 | Nexa (random devices) | Smart sockets, motion detectors, wall switches, remote controls, etc. Replaced all with ZigBee devices. The main drawbak of RF is that you never know if the signal reached the device or not.
  
## Configuration

### ESPHome

### Alexa

* Used [Alexa integration](https://www.home-assistant.io/integrations/alexa/) for controlling Echo devices.

* Home assistant lights and switches exposed via [Emulated Hue integration](https://www.home-assistant.io/integrations/emulated_hue/). 

* Tip: It is easier to manage smart devices via [alexa website](https://alexa.amazon.co.uk/spa/index.html#appliances).
