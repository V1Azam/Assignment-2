# Programming Black Assignemnt 2 Logs
wcqg59 - Muhammad Azam Bin Aminuddin

## Introduction
As a collaborative project for the 2nd Programming Black Assignment, me and a few other students have chosen to use our project buidling a self-trailing autonomous shopping cart within the Robotics society as our subject. 

Admittedly, although the project idea itself and groups have already been initialised very early on in the year, not much has been done as groundwork and hard coding. This assignemnet will be the oppurtunity to focus and learn about what entails in a robotics project from concept to final product (Though reaching the final stage is a huge ambition!)

### Project outline
I have segmented the overall project and assignment as 3 main goals/core values. 

1. **Maintain ambition to reach a final product.** This includes not being enclosed in feasibility, rather focusing on solutions to general and future issues and processes.

    This would allow for the oppurtunity to tackle more aspects in the whole process of product creation rather than being road blocked by an early issue.

2. **Investigate the not so computer science aspects of robot creation through its interaction with computer science.** As one of the few students who had selected an engineering module as the optional module for 1st year, I would also keep in mind the engineering physical trials and how it would be solved using the programs we would have to create.

3. **Exploration of other projects.** Though not particalry inspired by a certain past project by other people, I have no doubt the problems we will face have been discovered and solved by others before, in similar or completely different projects of their own. 

    I wish to explore and research what could be applicable for our case, as what better solution is there to a problem than a tested solution in which you can gauge success?

## Entry Log #1
Late LOG 22/03/2025 (written 19/03/2025)

In our initital set up and configuration of the NVIDIA Jetson Nano 2GB for development the team attempted to flash the Jetson OS (Jetpack) onto an SD card. Our hope was to successfully boot up the Jetson Nano and establish a working environment...

However, we had already encountered an issue where the wifi software seemed unresponsive. We could have spent the rest of the day trying to resolve the connectivity issues (WiFi and interfacing) however opted to work with what we had using Jetson's Headless mode through PuTTy's serial monitor via a HDMI-USB cable.

Despite this setback we were able to look forward with progress coinciding with the arrival of the team purchases, including: 

- A small LiDar sensor
- A board + cable to convert the lidars pinout to usb
- and An IMU (Inerital Measurement Unit).

### Next Steps
1. Research alternative methods to enable WiFi on the Jetson Nano (e.g., USB WiFi adapters compatible with ARM processors)

    *Despite making it work with a cable, regarding the nature of the final product, we hope to find a way to interact with the interface untethered for future convenience when debugging and tuning.*

2. Explore the documentation for the LiDAR sensor and IMU to gain an understanding of their data output and communication protocols.
3. Study general robotics concepts such as SLAM (Simultaneous Localization and Mapping) for autonomous navigation.