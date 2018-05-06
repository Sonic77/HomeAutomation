# Project: Body Weight Scale

## A little bit of history
Basicly i had a functioning scale ... that stopped working ... not sure what happend with it. With my limited electronics debugging knowledge i could not easily find a culprit.

A few months ago i played around with WS2812 RGB LED Strips and ESP01 with ESP2866 chip. I did not trust a old PC power supply to deliver 3.3V so i finally used a Raspberry Pi, but the ESP01 concept worked power from a USB programmer.

Researing the scale sensors i found a HX711 chip and projects of people using that the read out the scale weight sensors. A bit more research later i found a ESP2866 library, but the projects of them together were limited. Basicly it should be possible

## The plan
Create a easy to use WiFi enabled scale that will show your weight to your smartphone via a web-app.

## Research

## Modifications
* Adjust the battery compartment from 4xAA 4x1.5V in series to 2x2AA to supply 3V that should be enough to run the ESP01 and HX711.

