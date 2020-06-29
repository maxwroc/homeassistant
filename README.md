# Home Assistant configuration

## Add-ons
* HACS
* ESPHome

## Devices

| Connection | Brand | Model | Photo | Notes |
|:-----|:-----|:-----|:-----|:-----|
| WiFi |  |  |  |  |
|  | Sonoff | S20 | ![image](https://user-images.githubusercontent.com/8268674/85944365-1464b580-b92e-11ea-90a1-0f4fa9e6546d.png) | Smart plug; ESPHome firmware
|  | Sonoff | Touch | ![image](https://user-images.githubusercontent.com/8268674/85944447-b4bada00-b92e-11ea-8411-f785e0630398.png) | Smart wall switch; ESPHome firmware
|  | Shelly | 1 | ![image](https://user-images.githubusercontent.com/8268674/85944528-4fb3b400-b92f-11ea-8444-9ad851cfa497.png) | Smart switch; ESPHome firmware
|  | Tp-Link | HS110 | ![image](https://user-images.githubusercontent.com/8268674/85944585-c486ee00-b92f-11ea-857f-745ec5a34fc4.png) | Smart plug with energy monitoring
|  | Broadlink | RM mini 3 | ![image](https://user-images.githubusercontent.com/8268674/85944713-d3ba6b80-b930-11ea-8c70-c0141ee834b8.png) | IR remote controller (not configured yet)
|  | Sonoff | GK-200MP2-B | ![image](https://user-images.githubusercontent.com/8268674/86054006-49b5f400-ba51-11ea-8d85-fa57775cf387.png) | IP camera; Pan-tilt controlled via Home Assistant
|  | D-Link | DCS-932L | ![image](https://user-images.githubusercontent.com/8268674/86054297-cea10d80-ba51-11ea-9546-643240c78b7c.png) | IP camera
| RF433 |  |  |  | 
|  | RFXCOM | RfxTrxE | ![image](https://user-images.githubusercontent.com/8268674/86055023-183e2800-ba53-11ea-9aab-57f64a405b68.png) | USB RF transceiver
|  | OWL | OWL Intuition Gateway | ![image](https://user-images.githubusercontent.com/8268674/86055820-48d29180-ba54-11ea-9bfc-0a7a50e383f4.png) | Energy monitoring via CT (current transformer) sensor
|  | Nexa | LML-710 | ![image](https://user-images.githubusercontent.com/8268674/86056059-bb437180-ba54-11ea-9a1f-59221257fe99.png) | Doorbell
|  | Nexa | LWST-605 | ![image](https://user-images.githubusercontent.com/8268674/86056642-aca98a00-ba55-11ea-9d7d-29d0ad6ea21a.png) | Wall switch
| ZigBee |  |  |  |  |
|  | Phoscon | ConBee II | ![image](https://user-images.githubusercontent.com/8268674/86056863-0742e600-ba56-11ea-82e5-594602251075.png) | USB ZigBee transceiver

* WiFi
  * Sonoff S20
  * Sonoff Touch
  * Shelly 1
  * Tp-Link HS110
  * Broadlink RM mini 3 (not configured yet)
  * Sonoff GK-200MP2-B IP camera
  * D-Link DCS-932L IP Camera
* RF433
  * RfxTrxE
  * OWL Energy
  * Cotech doorbell
  * Nexa LWST-605 - wall switch
* ZigBee
  * ConBee II
  * Aqara motion sensor
  * Aqara temperature and humidity sensor
  * Aqara smart wall switch (double, mains powered)
  * Aqara smart wall switch (battery powered)
  * Aqara door sensors

Used in the past
* RF433
  * Telldus TellstickNet
  * Cotech motion sensor
  * Nexa wall button
  * Nexa remote control
  * Nexa motion sensor
* WiFi
  * Tp-Link HS100
  
  
## Configuration

### ESPHome
