---
title: Point Cloud
category: interactive
subtitle: Virtual Musical Instrument
thumb: /images/thumbs/pntcld.png
date: 2024-10-15
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/gJVo3uGK-lQ?si=O27N5m1d_nY5aeoA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Point Cloud was created using Unreal Engine 5 and Max/MSP, with both softwares communicating via OSC. In this system, a collection of sounds is sliced into points. Using the FluCoMa library in Max, the points are clustered based on how similar the sounds are to each other, creating a 3D point cloud of the sound corpus. I use a video game controller to perform this virtual musical instrument by flying through the point cloud at various speeds, activating the point by getting close to them. There are different sound effects I can activate with the game controller that I use to create more complex sonic gestures. These effects are represented by the color to which the points turn to upon activation. The coloringof the points also serves as a visual trail for the movement trajectories performed.