---
layout: post
title: 3D Nature Environment
subtitle: with procedurally generated terrain and trees
tags: [graphics, opengl, c++, procedural]
image: /img/2016-12-14/149%20-%20inparams1.png
bigimg: /img/2016-12-14/150%20-%20inparams2.png
---

This was my final project for the computer graphics course I took at the University of Waterloo (CS488). Much of the inspiration for this project comes from David Whatley's chapter in GPU Gems 2, [Toward Photorealism in Virtual Botany](http://http.developer.nvidia.com/GPUGems2/gpugems2_chapter01.html). The aim was to combine principles of procedural generation with other graphics techniques to create an immersive, organic environment. You can find the source [here](https://github.com/lozog/Procedural-Nature-3D).

The biggest objectives of this project are procedural generation of terrain with [Perlin Noise](http://staffwww.itn.liu.se/~stegu/simplexnoise/simplexnoise.pdf) and procedural generation of trees with [Lindenmayer Systems](http://algorithmicbotany.org/papers/abop/abop-ch1.pdf).

Features include first-person camera controls, procedural terrain generation with Perlin noise, model textures, a skybox, billboards (with a screen-door effect), procedural generation of trees with L-systems, water reflections, and shadows.

Below are five screenshots of the final project. Changing input parameters allow the user to generate different scenes.

![In-Program Screenshot 1](https://lozog.github.io/img/2016-12-14/149%20-%20inparams1.png "In-Program Screenshot 1")
![In-Program Screenshot 2](https://lozog.github.io/img/2016-12-14/150%20-%20inparams2.png "In-Program Screenshot 2")
![In-Program Screenshot 3](https://lozog.github.io/img/2016-12-14/151%20-%20inparams3.png "In-Program Screenshot 3")
![In-Program Screenshot 4](https://lozog.github.io/img/2016-12-14/152%20-%20inparams4.png "In-Program Screenshot 4")
![In-Program Screenshot 5](https://lozog.github.io/img/2016-12-14/153%20-%20inparams5.png "In-Program Screenshot 5")
