# Esp32-CNVG

Cheap night vision goggles with IPD adjustment, based on ESP32.

## Overview

A personal project focused on designing and building modular night vision goggles with adjustable IPD, distributed electronics and trying to make it as cheap as possible. The goggles are built by making two tubular modules, one for each eye, connected with a symmetrical rack and pinion system.

Currently in the planning and design phase.

Each eye module includes:
- ESP32-CAM to capture the image  
- 240x240 TFT display to show the video feed  
- 40mm Google Cardboard lens to enlarge the screen and improve viewing comfort  
- 3W IR LED system with driver for low-light illumination  

The camera captures the scene, processes it through the ESP32, and displays it directly on the TFT screen inside each eyepiece.

## Mechanical Design

- Two independent optical tubes (one per eye)
- Central IPD adjustment system
- Based on a 150mm T8 lead screw (right-left thread) or an alternative rack-and-pinion mechanism
- 3D printed structure using matte black PLA
- M3 screws and nuts for assembly and reinforcement

## Power System

- 5V voltage regulator for stable power delivery
- Battery charging module for Li-ion charging
- Central power distribution to both modules

## Concept

Each eye operates as an independent imaging pipeline, but both are mechanically synchronized through the IPD adjustment system. The goal is to build a low-cost, lightweight, and modular night vision-inspired headset using off-the-shelf components.

## Bill of Materials

- M3 screws — $2.49  
- M3 nuts — $1.99  
- 150mm T8 Lead Screw Right-Left Thread — $7.80  
- Sakata 3D Matte PLA black — $15.00  
- LED Driver 3W — $3.49  
- High power IR LEDs — $2.60  
- Battery charging module — $0.00  
- ESP32-CAM module — $14.00  
- Round 240x240 TFT LCD — $5.00  
- Google Cardboard lenses 40mm focal length — $2.00  
- 5V voltage regulator — $1.59  

## Total Cost

$56 - $70

<img width="457" height="350" alt="image" src="https://github.com/user-attachments/assets/23991ffb-3bde-455c-a69b-f260f19724b2" />
