# LYRA-Macropad-Work-in-Progress-

Macropad on custom PCB 

# Overview

A compact 9-key macropad featuring a clickable rotary encoder and a 1-inch monochrome OLED display for mode indication and visual feedback.
Originally based on an Arduino Pro Micro, the final version integrates the microcontroller directly onto a custom PCB, improving reliability, cable management, and design cohesion.

# Features

* 9 mechanical keys arranged in a 3×3 layout

* Rotary encoder with a clickable knob for mode switching

* Four programmable modes, for example:

   * Music control (volume, play/pause, next/prev)

   * Program shortcuts (e.g., Photoshop, CAD, or IDE macros)

   * Media / general desktop shortcuts

* 1-inch OLED display for mode display and live status feedback

* Fully custom PCB (in development) replacing the Arduino Pro Micro

Designed for QMK/VIA or Arduino firmware

# Planned Improvements

* Integrated ATmega32U4 MCU directly on PCB

* Optional USB-C connector

* Support for battery operation and low-power sleep modes

* Case design refinements for 3D printing or CNC milling

# PCB Top Side View

This PCB is only for prototyping purposes. The final build will feature MCU directly on the PCB without the development board.

<img width="1315" height="1177" alt="image" src="https://github.com/user-attachments/assets/8776c888-d379-4e89-a7f6-f5ac97b3565d" />


# Update - 04.11.2025

Moved diodes from top layer to the bottom. Added diode to the encoder. Added hotswap sockets to switches for quick and easy replacement. Added mounting holes for case. (Below is the bottom side of the board)

<img width="1273" height="1184" alt="image" src="https://github.com/user-attachments/assets/fd10bc57-435f-4a0a-95c3-5d14a696481f" />

# Update - 09.11.2025

Replaced Arduino Micro with Arduino Pro Micro. Board will be sent to production soon.


