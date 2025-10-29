# USB-Powered LED Dimmer Board

A compact USB-powered LED dimmer using a 555 timer in astable mode to generate PWM for LED brightness control. Built with KiCad and designed for learning, testing, and prototyping.

## Features
- 5V USB input with polyfuse and ESD protection
- Adjustable PWM (up to 1.2 kHz)
- NMOS transistor output stage for LED strips
- Compact 2-layer PCB layout

## Components
- **U1:** USBLC6-2SC6 (ESD Protection)
- **F1:** Polyfuse 555
- **U2:** NE555P Timer
- **Q1:** N-channel MOSFET
- **D1, D2:** Diodes (Protection & Indicator)
- **R1–R5, C1–C2:** Timing and filtering components

## How It Works
PWM duty cycle from the NE555 determines LED brightness. The NMOS transistor switches the LED strip according to PWM output, with frequency beyond visible flicker range.

## Applications
- USB LED dimmer
- PWM circuit learning
- Small electronics projects
