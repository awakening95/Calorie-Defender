# Calorie Defender

Calorie Defender는 다이어트의 실패 원인 중 가장 큰 부분을 차지하는 식욕을 억제할 수 있도록 도와주고자 하는 카드 케이스로 사용자가 지정한 고깃집, 패스트푸드점, 디저트 가게 등의 장소에서 카드 케이스가 열리지 않도록 함으로써 카드를 사용할 수 없게 한다.

**※ Calorie Defender는 전자부품연구원(KETI)에서 제공하는 오픈소스 IoT 플랫폼인 Mobius를 이용하여 제작되었다.**

![Calorie Defender](https://github.com/awakening95/etc/blob/master/Calorie%20Defender/Calorie%20Defender.gif?raw=true)

## 목차

- [Overview](#overview)
- [Components](#components)
- [How to use](#how-to-use)

## Overview
Calorie Defender는 다음과 같이 구성된다.

![image](https://github.com/awakening95/Calorie-Defender/blob/master/images/Overview.png) 

## Components
Calorie Defender의 장치는 다음과 같이 구성된다.

![image](https://github.com/awakening95/Calorie-Defender/blob/master/images/Components.png)

각 장치의 pinout은 How to use 의 1번에 설명되어 있다.

## How to use

### 1 Pinout

먼저 장치를 이용해 다음과 같이 연결한다.

<image src = "https://github.com/awakening95/Calorie-Defender/blob/master/images/Calorie-Defender_pinout.png" width=500>

| **MPU-6050 (Gyro Sensor)** | **SG -90 (Servo Motor)** | **Adafruit Ultimate GPS Breakout:ada-746 (GPS Module)** |
| :--------: | :--------: | :--------: |
| VCC - 3V | Red( VCC ) - 3V or 5V  | 3.3V - 3V |	
| GND - GND | Orange (PWM ) - 9~| TX - RX |
| SCL - SCL | Brown(GND) - GND | RX - TX |
| SDA - SDA |  | GND - GND |

***베터리의 경우 3.7V의 500mAh 리튬 폴리머 배터리를 사용하였으나 2.54mm pitch 를 지원하는 다른 베터리를 사용해도 무방하다.***

### 2


### 3
