---
layout: post
title: "WannaBrain?"
date: 2017-11-03
categories: 
  - PhyComp
description: 
image: 
image-sm:
---

# Wanna a Brain?: Midterm
------


## Brief

Let's make something for Halloween. We didn't wanna thought about technology, instead, we decided to think about a Halloween product to share with our audience regardless the tech involved. Personally speaking, I can say this is the first project I've made just for fun, thinking what are the feelings we want to produce in people. Now, I feel that's the right and only way to do it. Just ask to ourselves: What do we want to communicate?. 

## What to produce?

We wanted to produce Halloween feelings of course!. Thinking about the format, target and place we decided to hide every tech clue about our device, in order to create a freak, repulsive experience where the people would share, laugh and wonder.  
For some reason the first thing which came to our minds was food. Mostly interaction in Halloween it's about get and give some food, sweets, chocolates, etc. Let's give interactive food. How weird can that sound?. That's being said, it was sort of easy to picture what we wanted. 

## References

Head in jars from futurama was the main reference. These floating heads in jars of different personalities. What about the opportunity of taste that water, those faces or eat those brains. The brain shape gave us a character with no identity who can be anyone, different voices and faces.

![Interactivity](/assets/wannaBrain07.png)

## Concept

Once the basis were thought, we started deliberating about several parts of our system. We thought about the timeline experience which is: people are gonna approach to this repulsive food being invited to eat it. They would try to eat it and then they would be aware of its "active" state.
Let's think about this device as a system which has inputs, procceses, outputs and maintenance.

### Inputs:
	1. touch

### Processes:
	1. Give the brain a voice and a face - Identity
	2. Come to live 

### Outputs:
	1. Speak
	2. Move
	3. Light up
	4. Show a face

### Maintenance:
	1. We made a cardboard box with access in the bottom face (just in case we need quick access).
	2. We realized people might not be interested in eat it because of sanitary issues. 
	We came with extra materials as foil and plastic wrap.
	3. The food would be the last part to assemble to ensure cleanliness.

## Technical solution
	
	We decided to use this schematic.

![Interactivity](/assets/wannaBrain06.jpeg)

	1. Capacitive sensor: based on CapSense library for Arduino to trigger action.
	2. Button: to trigger actions in case of emergency.
	3. 8 Ohms Speaker as sound output
	4. Record and playback module ISD1820 to record a message in loop "EAT THE BRAIN"
	5. Servo motor to shake the brain
	6. 8 lEDS connected to a Shift register.
	7. p5.js sketch to trigger images and audios
	8. JELLO as a main material. 
	It is conductive (metal spoons) to use as a bridge between the circuit and us as a capacitors.


## Process:
![Interactivity](/assets/wannaBrain02.png)
![Interactivity](/assets/wannaBrain03.gif)
![Interactivity](/assets/wannaBrain04.png)
We made jello several times because we didnt reach enough density to mantain a firm shape.
![Interactivity](/assets/wannaBrain05.jpeg)

## Experience:
![Interactivity](/assets/wannaBrain.png)
![Interactivity](/assets/wannaBrain01.png)

The best is her face!. 

## Technical issues

- 8 Ohms speaker's power is nothing (too low). As a recomendation, It's useful to have a built-in amplifier module to make it louder.

- When you touch the jello, you make it shake indeed, so the shake feedback produced by the servo is almost invisible.

- LEDs have focused light. In order to make it more uniform distribuited you should use a diffuser.

- Movement of the capatitor, in this case the jello could activate the capacitive sensor, triggering the experience. Your should be sure you have callibrated a right threshold.
