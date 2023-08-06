# Repurposing Old Hardware: NAS (Network Attached Storage)


## Overview
For this short home project I wanted to work with hardware and repurpose an old machine that did not function as something useful on my local network: a NAS. The computer will be able to locally host files at a static IP, and will also be running as a personal media server.




## 1. Hardware

### This computer has had a corrupt drive and been left untouched for 5 years, so I need to first do a few things to the hardware:
- Clean and dust internals, so the air can properly flow.
- Remove old corrupt HDD and install new SSD.
- Disassemble and reapply thermal paste on GPU & CPU.










## 2. Software

### Installing Ubuntu, Server config, and Network config:


- The most challenging part of this project was the left-behind artifacts from the corrupted Windows OS that ran on the original drive. 
- The machine will boot to Ubuntu but will not properly install, and is stuck in a loop asking for Windows Bootable Media.
- I fixed this by first clearing the CMOS with a jumper/removing the on-board battery and then changing the Ubuntu version to the LTS (Long Term Support) version.



- Next I wired the computer into my network and gave it a static IP for ease of use.

- Install an OpenSSH server for secure communication.
- Install Plex to run a local Media Server.
