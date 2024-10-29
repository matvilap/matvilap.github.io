---
title: push and pull
category: interactive
subtitle: Music Interaction
thumb: /images/thumbs/gravityonmyhands.png
date: 2022-01-15
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/XL6pVQ2yRmE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*push and pull* is performed in a virtual environment that enables the performer to articulate musical gestures through a virtual extension of their physical body. Through a combination of gestures and controller input the performer can manipulate floating orbs using simulated gravitational forces to control sound generating collisions between the orbs and other objects.

Each of the objects in the scene has a specific virtual instrument assigned to it. This is achieved through OSC communication between Unity 3D and Ableton Live, where collision data is mapped to the MIDI input of different virtual instruments. Pitch is determined by the size of the floating orbs, while other parameters such as velocity and note length are mapped to the speed value at the moment of collision between virtual objects.
