# CurrentSensor
## Prototype Schedule
1. Planning and buy material (05/05)
2. Breadboard Prototype (05/10)
3. Prototype with ACS712 (05/13)

## Exp Schedule
1. Planning exp

## Material
1. UNO
2. ACS712 and 1 ohm(1/16watt)
3. bread board
4. jumper wire

![](https://i.imgur.com/nmkM3XW.png)

## Calibration Process
This process will modify Vref and sensitivity.
1. While the motor is disconnected, the output should be zero. So, modify the Vref so the output can be zero.
2. Serial a current meter, modify sensitivity to make output equal to current meter.

REF:
Using Resistors for Current Sensing: It’s More Than Just I = V/R
https://www.powerelectronics.com/technologies/power-management/article/21864130/using-resistors-for-current-sensing-its-more-than-just-i-vr

## Current sensor by using ACS712
Serial ACS712 module and current meter between Motor side and ground side.
Follow calibration process. Then, it is able to get proximate current value. 

## Current sensor by using Resistor
Serial 1 ohm 1/16 watt resistor and current meter between Motor side and ground side.
Follow calibration process. Then, it is able to get proximate current value. 

### Problems
The sensitivity values are not the same while measure 50mA and 90mA target. Still investigate this phenomena.


REF:
1. current sensing
SparkFun Low Current Sensor Breakout Board - ACS723
https://github.com/sparkfun/Current_Sensor_Breakout-ACS723-Low_Current

Arduino library for ACS712 current sensor
https://github.com/rkoptev/ACS712-arduino

2. GUI
GUIslice library
https://github.com/ImpulseAdventure/GUIslice
