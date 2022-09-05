# Loom Pedals: Raspberry Pi

The loom pedals are a hardware peripheral interface for the TC2 digital Jacquard loom by Tronrud Engineering. They have been designed as a modular system of foot pedals, similar to guitar effects pedals used by musicians, which are connected via a Raspberry Pi to a web-based open source weaving software, [AdaCAD](https://github.com/UnstableDesign/AdaCAD). 
 
This repository contains the code for the Node.JS program which runs on the Raspberry Pi to maintain connects to the pedals, TC2, and AdaCAD. ***NOTE:*** not all parts of the code are currently public. We are working out how to share these details.

## Directory

>  0. Main modules
>  1. Pedals driver
>>    * Debugging module for emulating a set of pedals on a webpage
>  2. TC2 connection *(not yet public)*
>  3. Database connection