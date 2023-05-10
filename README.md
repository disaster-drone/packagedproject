# *State Farm Disaster Drone Packaged Project*

### Table of Contents
1. [Description](#Description)
2. [Demo](#Demo)
3. [Installation](#Installation-Proccess) 
4. [Hardware & System Requirements](#Product-Specs)
5. [Migration Notes](#Migration-Notes)
6. [Controls](#Controls)


## Description
This project contains a sample VR project ready to run on Windows.

## Demo
**Full Demo Video:** https://youtu.be/faXq7GY65Ww

## Installation
**Prerequisites**

Download Unreal Engine Editor Version: 5.0.3-20979098+++UE5+Release-5.0.
Download the Oculus App on your Desktop.
Set up your VR Headset on the Oculus App.

**Download**

- Download the [packaged VR Environment executable](https://github.com/disaster-drone/packagedproject/releases/latest)
- Extract the compressed file in any folder
- Launch the **launchgame.py** python script and it will launch the executable

> To view the controls for the VR environment, [click here.](#Controls)


## Hardware & System Requirements
The System should function correctly with:
* Oculus Mobile: Quest 1 and Quest 2
* Oculus PC: Rift S and Quest with Oculus Link. 

However, it was only tested with the Oculus Quest 2 and the Oculus Rift. We recommend the Oculus Quest 2. https://www.meta.com/quest/products/quest-2/


**Recommended Hardware and System Requirements for the Oculus Rift:**
* Processor: Intel i5-4590/AMD Ryzen 5 1500X or greater
* Graphics Card: NVIDIA GTX 1060/AMD Radeon RX 480 or greater
* Alternative Graphics Card: NVIDIA GTX 970/AMD Radeon R9 290 or greater
* Memory: 16 GB RAM
* Operating System: Windows 10
* USB Ports: 1 x USB 3.0 port (3x USB for Oculus Rift C1)
* Video Output: Compatible DisplayPort


**Recommended Hardware and System Requirements for the Oculus Quest 2:**
* Processor: Intel i5-4590 / AMD Ryzen 5 1500X or better
* GPU: NVIDIA GeForce GTX 1070 or AMD 500 Series and higher
* Memory: 8 GB RAM
* Operating System: Microsoft Windows 10
* USB Ports: 1x USB port
* Note: The Oculus Quest is a tetherless device but you may choose to purchase Oculus Link cable to connect the Oculus Quest with your PC due to frequent connection timeouts.

System requirement information gathered from: https://circuitstream.com/blog/vr-hardware

## Controls
**Movement**
* Teleport
    * Move your right motion controllers thumbstick in the direction you want to move. The teleport visualizer will appear in the level to indicate where you will move to.
    * Release the thumbstick to teleport to the selected location.
    * <img src = "https://github.com/disaster-drone/VR-Environment/assets/94029910/71eb150e-0697-4b78-a74e-e419bf89e39a" width="300">

* Fly
    * Fly up: Press the right innter grip to teleport up.
    * <img src = "https://github.com/disaster-drone/VR-Environment/assets/94029910/9e881049-3215-44cb-a6b8-ee640c761122" width="300">
    * Fly down: Press the left inner grip to teleport down.
    * <img src = "https://github.com/disaster-drone/VR-Environment/assets/94029910/15e93d70-f960-481e-ae95-b33b7fc004c3" width="300">
* Snap Turn
    * To rotate your virtual character without moving your head, move your left motion controller's thumbstick in the direction you want to turn.
    * <img src = "https://github.com/disaster-drone/VR-Environment/assets/94029910/2fc62ac1-e419-4975-87eb-5d319089e425" width="300">


**Make a Claim**
* Place a Cone
    * Hold down your right motion controllers back trigger in the direction you want to place the cone. The place a cone visualizer appears in the level to indicate where the cone will be placed.
    * Release the trigger to place the cone in the selected location and toggle the UI that displays the closest camera angle.
    * <img src = "https://github.com/disaster-drone/VR-Environment/assets/94029910/558f944c-24dd-4b34-b7ad-01bac14f6f01" width="300">
* UI
    * After placing a cone, a UI menu will pop up attatched to your right motion controller.
    * To click buttons on the UI use the left motion controllers laser pointer to hover over the button you wish to press.
    * To press the button click the left motion controllers back trigger.
    * <img src = "https://github.com/disaster-drone/VR-Environment/assets/94029910/f6918c73-5f95-4c1b-94d1-07da666bcddd" width="300">

