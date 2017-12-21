---
layout: post
title: "Unity First Scene"
date: 2017-12-10
categories:
  - Animation
description: 
image: 
image-sm:
---

### Unity First Scene



I had previous experience with 3D softwares regarding modelling, rigging and animation. This knowledge have helped me working with 3D Engines since the process of navigating between cameras and 3d viewports is intuitive and straightforward. I decided to mix what I've learnt so far + some code.
So first things first I used a character from Adobe Mixamo with the basic animations (walking and running to the left and right) and map this movements to the keys UP, DOWN, LEFT, RIGHT. At the same time I parented the camera to the character (disabling rotation) in order to have a simple third person camera. I wanted my character to have a ground and to collide with every element in my scene which demanded a Rigidbody and a Collider per component.

![Enlighten](/assets/Unity.png)
![Enlighten](/assets/Unity01.png)
![Enlighten](/assets/Unity02.png)


I made really simple scenario with multiple cubes with differents sizes. The amount of cubes depended on the size of the ground and a random function to determine the position within X,Z axes. Physhics and 0 gravity allow the cubes to float and react to the collisions once they happens. I coded a little script to trigger a sound every time the engine detects a collision. This sound was introduced in an Audio Clip component and associated with a Audio Source. Everytime there is a colllision the pitch of the sound varies randomly to produce a different tone. Finally we changed the color of the already touched cubes. That's the result.

[Unity - 3D](https://www.youtube.com/watch?v=Aw3AwK74wWQ)
{% include youtubePlayer.html id="Aw3AwK74wWQ" %}