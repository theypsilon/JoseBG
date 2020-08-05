---
title: Mini ECS.
description: Minimalistic ECS library for Unity3D
date: 2018-01-01
tags:
    - Unity 3D
    - Library
layout: layouts/project.njk
---
Minimalistic ECS framework for C#

I used it in [World War IX](http://localhost:8080/projects/wwix/), in a time where old component system was very limiting.

[Github repository here](https://github.com/theypsilon/MiniECS/)

## Technical Details

It is very easy to use, as it doesn't require code generation, and it's a fairly small library.

I optimized it for speed and to avoid any in-game memory allocation. It runs much faster than the Pre-DOTS Unity Component System in a large variety of benchmarks I performed, and it gives you much more control over the frame execution.

The drawback is that is a bit verbose.