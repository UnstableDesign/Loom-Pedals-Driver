# Loom Pedals: Driver Software

The loom pedals are a hardware peripheral interface for the TC2 digital Jacquard loom by Tronrud Engineering. They have been designed as a modular system of foot pedals, similar to guitar effects pedals used by musicians, which are connected via driver software to a web-based open source weaving program, [AdaCAD](https://github.com/UnstableDesign/AdaCAD). 
 
This repository contains Node.JS programs for different possible configurations of the Loom Pedals hardware, maintaining connections to the pedals, TC2, and AdaCAD. The **physical pedals** version requires a Raspberry Pi running Node.JS, along with the pedals hardware. The **virtual pedals** version does not require any hardware outside of the user's personal computer and existing TC2 hardware. ***NOTE:*** not all parts of the code are currently public. We are working out how to share these details.

## Requirements
* Local Wi-Fi network
* TC2 Digital Jacquard Loom
* Personal computer
* *(physical pedals)* Raspberry Pi
* *(physical pedals)* modular pedal units

## Directory

>  0. Main modules
>  1. Pedals driver
>>    * Debugging module for emulating a set of pedals on a webpage
>  2. TC2 connection *(not yet public)*
>  3. Database connection
