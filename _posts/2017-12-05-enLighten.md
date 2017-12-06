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

## EnLighten

With this, I've changed three times my idea. Finally, I've found something which responses to my wishes. Every idea has had a physical phenomenon involved: waves, light refraction and reflection, mirrors, fluids dynamics, inertia, etc. I realized this is not a new trend in my preferences, being that since I was a kid I encouraged myself in using practical experiments to understand concepts. Concepts => Practical uses => Interactive solutions.

EnLighten studies the fire as a fluid and allow us play with its movement in a secure way. Technically speaking, I've been interested in getting out from the 3.3 - 12 volts provided by the arduino and other microcontroller boards, making bigger installations as well. Unfortunately, these wishes make everything more expensive because of quality and quantity of materials. As a first experiment with these kind of projects (talking about current and size) I will work with bulbs (domestic and cheapy elements) in order to visualize the flame's behaviour.


This elements together suggest the idea of tempeture, light and image measurement and deployment. However, the mystism and romaticism implied in the fire is huge and I dont want to screw up it. That's why the tech part should be almost invisible taking advantage of the fire's dynamic as an input. In other words I will measure the fire's intensity, direction, state, size to generate related outputs. How many interactions are we able to have with a single flame?. Let's remove the buttons, sliders, levers, handle interfaces created for the human being when there are so many organic interfaces we can take advantage of, meanwhile, we may end up amplifying their feedback.

What do I want to produce in the people?: I want them to perceive the fire from other perspectives and play around it in some other ways they, we have forgotten.

### Installation

![Enlighten](/assets/enlighten.jpeg)

### BOMs - Bill of Materials

I will use 15 bulbs. Unfortunately it is impossible to dimmer and control brighness with just a relay. A much complex circuit is needed. Thanks to diy_bloke and his tutorial [Arduino Controlled Light Dimmer](http://www.instructables.com/id/Arduino-controlled-light-dimmer-The-circuit/).
These are the materials in order to control ONE BULB

1. 4N25 €0.25 or H11AA1 or IL250, IL251, IL252, LTV814
2. Resistor 10k €0.10
3. bridge rectifier 400 Volt €0.30
4. 2x 30 k resistor 1/2 Watt (resistors will probably dissipate 400mW max each €0.30
5. 1 connector €0.20
6. 5.1 Volt zenerdiode (optional)
7. LED (Note: you can replace the LED with a wire bridge as the LED may sometimes cause the lamp to flicker rather than to regulate smoothly)
8. MOC3021 If you chose another type, make sure it has NO zero-crossing detection, I can't stress this enough DO NOT use e.g. a MOC3042
9. Resistor 220 Ohm €0.10 (I actually used a 330 Ohm and that worked fine)
10. Resistor 470 Ohm-1k (I ended up using a 560 Ohm and that worked well)
11. TRIAC TIC206 €1.20 or BR136 €0.50
12. 1 connector €0.20

Multiply by 15 :D. Thats why the size matters.
Addionally, we will need.

1. 15x Bulbs and plugs
2. 2x Web cameras
3. Tempeture sensor.
4. 100 meters AC wire.
5. Capacitor - CapSense Arduino Library
6. Candle
7. 15x Piezo sensors
8. Arduino UNO.

### Action plan - Dates

 + Nov 20 - 24 -----------------------------
 	- Circuit Schematic. Ports budget.
 	- Construction one Bulb AC Dimmer and testing with arduino software
 	- Buy all materials
 + Nov 27 - Dic 1 -----------------------------
  	- AC load testing 20 bulbs = what voltage / what current?
 	- Build 20 different AC bulbs. DC Controller and Piezo installation
 + Dic 4 - 8 -----------------------------
  	- Bulding 3D model - bulbs as a pixels.
 	- Flame image analysis.
 	- Get scenography.
 	- Location definition.
 	- Final documentation
 + Dic 11 -----------------------------
 	- Final presentation.





