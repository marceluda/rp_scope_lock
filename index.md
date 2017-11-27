---
title: Scope+Lock
description: An oscilloscope + lock-in amplifier for RedPitaya
layout: page
---

Scope+Lock is an application for the [RedPitaya](https://redpitaya.com/) enviroment/board
that implements an Oscilloscope aplication and a Lock-in amplifier. It's based on
[relese-0.95 scope application](https://github.com/RedPitaya/RedPitaya/tree/release-v0.95/apps-free/scope)
of the RedPitaya project.

The aim of this application is to provide a toolkit for labs measurements and control applications.

## Features

- Web control interface
- Python based remote control designed for Spyder
- Complete Free Software source code.
- Oscilloscope application
- Lock-in amplifier (only with local oscillator)
- Modulation generator
  - Harmonic functions (from 3 Hz to 50 kHz)
    - Two 1f functions in quadrature (sine and cosine)
    - One 1f function with phase control
    - One 2f function  with phase control
    - One 3f function  with phase control
  - Square functions (from 30 mHz to 31 MHz)
    - Two 1f functions in quadrature
    - One 1f function with phase control
- Scan control
  - Triangle scan generator
  - Auto-lock / relock system
- Two configurable PID filters
  - Proportional, Integral and Derivative controllers
  - Set-point control
  - Several order of magnitudes
- Lock controller
  - System for making closed-loop stabilization schemes
  - Graphic tool for lock start-point selection

## Applications
