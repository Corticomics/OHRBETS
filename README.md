# Open-Stage: An Open-Source Platform for Head-Fixed Operant and Consummatory Behavior
<p align="center">
  <img src="./images/system_render.png" width="800">
</p>

Accompany to Gordon-Fennell et. al. 2023 *Journal* <!-- insert link -->

## Overview
Here we make available an ecosystem of open-source hardware and software for operant and consumption experiments in head-fixed mice. For operant responding, mice rotate a wheel in one of two directions and operant responding is gated using a mechanical wheel break. For consumption, mice consume liquid solutions from a metal lick spout and access to the spout is gated using retraction and extension of the spout. The system also includes optional multi-spout hardware that allows fixed access to 1 of 5 spouts. Using the hardware, behavioral software, and analysis software included in this repository, the Gordon-Fennell et. al. 2022 reproduced operant and consummatory behaviors established in feely-moving mice. The system presented here offers a scalable option for these behavioral approaches and is compatible with head-fixed imaging techniques including 2-photon imaging.  

The hardware consists of 3d printed and other low-cost components including micro servos that can be easily assembled with our detailed step-by-step guide. The system utilizes an Arduino Mega to control hardware including servos, solenoids, and tone generators, and to record behavioral events including licks and wheel rotation. Session parameters and behavioral events are recorded using a PC connected to the Arduino via USB. 

The Arduino software includes programs written in the Arduino language. We have included multiple scripts for different behavioral approaches including operant conditioning and multi-spout brief access. We have also included scrips used to setup for behavior and trouble shoot the system.  

The Analysis software includes programs written in R and relies on user created spreadsheets. We have included a universal decoder that parses the data produced by the Arduino. We have also included scripts for analyzing data produced by the generic operant conditioning and multi-spout brief access task Arduino programs.

We will continue to update this repository and add additional hardware and software. We welcome contributions that add on to our system for different behavioral designs.  
## Up to Date Resources
- [Purchase List](https://docs.google.com/spreadsheets/d/1kFgsOy1gAFHM2E8M-DSgPSi6Y7Lr8sis6cbQqSb2ZY4)
- [3d Printing File Key](https://docs.google.com/spreadsheets/d/1pzRUh2JkpAaJyb1kA9NBVjSYz8nG3GPTu3c0QVQwKCg)


## Contributors
Adam Gordon-Fennell (University of Washington), Garret Stuber (University of Washington)
