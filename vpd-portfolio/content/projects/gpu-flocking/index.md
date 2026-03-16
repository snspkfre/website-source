---
draft: false
title: 'GPU Flocking'
featured: true
tags: ['Unity', 'HLSL', 'Shadergraph']
---

<br>

<div style="float: right; min-width: 250px; width: 700px; max-width: 650px; margin-left: 20px; margin-top: 10px; gap: 20px">

{{< carousel images="carousel-images/*" aspectRatio="16-9" interval="2000">}}

</div>

<br>

# About

This project was my final project for a course intermediate graphics and animation programming. Our goal was to create an environment with fish that were flocking and make it look like a painting via a kuwahara filter. 

In order to have the fish flock in an efficient manner we went about implementing the flocking by utilizing GPU dispatches through a compute shader. 

<br>

# Responsibilities

- Implemented the flocking algorithm such that it calculates boids on the GPU using compute shaders to save performance
- Reduced performance to be able to calculate the position and velocity thousands of boids simultaneously while maintaining a stable 60 FPS
- Implemented instanced rendering of boids so they work with vertex shader animations created in shader graph

# Info

- Role: Compute shader flocking algorithm
- Team Size: 3
- Development Time: 3 weeks

<br>