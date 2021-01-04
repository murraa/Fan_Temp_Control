# Temperature Controlled 4-Pin Fan /w Arduino Nano

## Intro
This code was written to control the temperature inside a server cabinet by measuring the temperature
with an DS18b20 Temperature probe and outputting a PWM signal with the arduino nano to control a 4-Pin fan.
Unlike the cheap control boards from amazon or ebay this code switches the fan off when the temperature
is low enough.

## Overview:
...

## Features
Defining features of the code:
- simple code which can be easily altered or extended
- serial output for easy debugging
- adjustable parameters

## Acknowledgment
These two projects were used for inspiration and code snippets, especially the pwm timer part:
- for basic structure: https://create.arduino.cc/projecthub/KaptenJansson/pwn-fan-controller-with-temp-sensing-and-button-override-4f2e8d/embed
- for PWM timers: https://fdossena.com/?p=ArduinoFanControl/i.md