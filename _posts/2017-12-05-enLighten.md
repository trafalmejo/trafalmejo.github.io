---
layout: post
title: "EnLighten - Part 02"
date: 2017-12-05
categories: 
  - PhyComp
description: 
image: 
image-sm:
---

## Testing

First testes shows there are glitches in the lower voltages, so knowing that working between 10% and 30% of the power is working fine (50% is too brigth to enjoy the experience but you can go up to 90% easily if you want to). So far there are not significant differences between LED and Tradional bulbs so in the first testes i am mixing them without bigger issues.

![Enlighten](/assets/8channel.jpeg)

Regarding the flame's movements tracking, it could be accomplished by using image analisys and video input but it would include camera setup and callibration according with light from the environment (this is necessary in almost all scenarios I can imaging). The addional problems with the camera includes shadows casting, color callibration, resolution, tele lenses, point of view, blind spots, etc. I decide to use 4 light sensor in the NORTH, SOUTH, WEST, EAST locations related with the candle. Every photoresistor will give us analog values from 0 - 1023 of how much light is receiving each corner (almost like x and y factors).

In our ideal scenario the flame is giving the same light to every sensor, but if there is more light in one sensor than another it means the flame has a direction. This baheviour allow us to make this relation:

X position = EAST - WEST;
Y position = NORTH - SOUTH;

This resulted values are the direction vectors of the flame related with a coordinate system at [0,0];
For example, is all the NORTH, SOUTH, WEST, EAST are 1023 that means X and Y = 0 which means no direction, because all the sensors are reading the same quantity of light. The cool of this is the noise implied in a flame's movement which moves the readings every time.
The first set Up included uncovered sensors but they didnt work because they were receiving external data from environment light. Convered sensors focus on sensing our flame.

![Enlighten](/assets/photoresistors.jpeg)

The first prototype was made in cardboard which is not the more friendly material with fire. So far I haven't had any sort of issue with it, but it is crucial to change the materials to avoid incidents.

## Simulation

Enlighten will controlled the brighness of 8 bulbs in the space depending on where they are, meaning, their relation with the flame. In order to make this happen I designed a 3D simulator where the bulbs can be placed whereever its necessary. This app make the experience editable and scalable (this may include new features in the future). The simulator include a particle system which simulates a virtual flame which responses to virtual wind. Brightness and wind's direction is controlled by our SERIAL readings from ARDUINO and going back to dim every bulb.


![Enlighten](/assets/simulator.jpeg)
