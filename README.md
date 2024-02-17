# LED Blinking Program using Raspberry Pi

## Overview

This repository features a basic LED blinking program designed for the Raspberry Pi. The project aims to showcase the fundamental process of controlling an LED through Raspberry Pi GPIO pins.

## Pin Setup

Connect the components as follows:

- PIN: 3
- GND: 6
## Code
```
import RPi.GPIO as GPIO
import time
GPIO.setmode(GPIO.BOARD)
GPIO.setup(3,GPIO.OUT)

while True:
    GPIO.output(3,True)
    time.sleep(1)
    GPIO.output(3,False)
    time.sleep(1)
```

## Screenshot-:
![image](https://github.com/Niltiwari7/Raspberry-pi-led-blinking/assets/93751356/db6cb953-4bd4-4eca-878c-4ec9762fa332)
