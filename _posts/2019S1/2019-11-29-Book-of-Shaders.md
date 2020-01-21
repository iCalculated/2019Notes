---
title: "Book of Shaders"
date: 2019-11-29
math: true 
categories: [Computer Science]
---

### Uniforms

Any data that is shared between all threads

- `u_resolution` the resolution of the screen
- `u_mouse` the mouse location, in pixels
- `u_time` time in seconds since load

### Varying

Changes per thread

- `gl_FragCoord` a vec4 with x and y values
- `gl_FragColor` a vec4 rgba output