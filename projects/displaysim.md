---
title: Display Sim
description: Tool for recreating vintage display technologies.
date: 2019-01-01
tags:
    - 3D simulation
    - Retro Gaming
layout: layouts/project.njk
---
This tool allows you to recreate CRT displays of many kinds. It's still on early development, and requires a good graphic card, because the generated filters make sense on resolutions equal or higher than 4K, and each prixel is processed individually.

The backend is implemented in Rust language compiled to WebASM and using WebGL.

The fronted is pure Vanilla JS using a minimalistic view rendering aproach.

## Relevant Links

Repository: https://github.com/theypsilon/display-sim

Demo (high GPU usage): https://theypsilon.github.io/display-sim/