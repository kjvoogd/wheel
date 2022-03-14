# [Table of Contents](#table-of-contents)
- [ESP32 WROOM 4Mb Devkit](#esp32-wroom-4mb-devkit)
  * [ESP32 pin out](#esp32-pin-out)
- [SBC oled-01](#sbc-oled-01)
  * [SBC oled-01 pin out](#sbc-oled-01-pin-out)
- [neopixel](#neopixel)
  * [neopixel pin out](#neopixel-pin-out)
- [MD10C R3](#md10c-r3)
  * [MD10C R3 pin out](#md10c-r3-pin-out)
- [HC-SR04](#hc-sr04)
  * [HC-SR04 pin out](#hc-sr04-pin-out)





# ESP32 WROOM 4Mb Devkit

## ESP32 pin out

<img width="600" alt="pin_out" src="https://user-images.githubusercontent.com/2764526/156782730-9ac44796-3b3b-435d-a7ad-12cfd2f4369e.png">

# SBC oled-01

![sbc_oled01](https://user-images.githubusercontent.com/2764526/156784333-1f9d4fbf-3262-40e4-98df-267356fde660.png)

## SBC oled-01 pin out


| OLED          | Uno       | ESP32  |
| ------------- |-----------| -------|
| GND           | GND       | GND |
| VCC           | 3.3 V     | 3.3 V |
| SLC           | A5 (SCL)  | D22 (GPIO 22) SLC |
| SDA           | A4 (SDA)  | D21 (GPIO 21) SDA |


# neopixel

![neo_pix](https://user-images.githubusercontent.com/2764526/158013567-5196e040-185d-43bf-9cd6-9a11063a85bd.png)

## neopixel pin out

| RING          | Uno       | ESP32  |
| ------------- |-----------| -------|
| GND           | GND       | GND |
| VCC           | 3.3 V     | 3.3 V |
| Data In       | 6 (PD6)   | D27 (GPIO 27) |

# MD10C R3

![cytron-md10c-single-channel-30v-13a-motor-controller](https://user-images.githubusercontent.com/2764526/158017036-976b7955-9e02-48b5-b190-70e78db6831f.png)

## MD10C R3 pin out

| MD10C R3      | Uno       | ESP32  |
| ------------- |-----------| -------|
| DIR           | 2         | D25 (GPIO 25) |
| PWM           | ~3        | D26 (GPIO 26) |
| GND           | GND       | GND |

# HC-SR04

![15569-Ultrasonic_Distance_Sensor_-_HC-SR04-01a](https://user-images.githubusercontent.com/2764526/158021524-edf9be96-b6f2-4d2b-ab40-ebf9d7039d1e.jpg)


## HC-SR04 pin out

| MD10C R3      | Uno       | ESP32  |
| ------------- |-----------| -------|
| VCC           | 5V         | D25 (GPIO 34) |
| Trig           | D3        | D26 (GPIO 35) |
| Echo           | D2       | GND |
| GND           | GND       | GND |


