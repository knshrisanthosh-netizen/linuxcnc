# DIY CNC VMC using linuxcnc
## Project description :
In this project I built a three axis cnc vmc using linuxcnc with parellel port to understand how cnc works from ground up.

## Table of contents :
- [Material used](#Materialused)

#### Material used : 


- MACH3 parallel port break out boaed

- Nema 23 open loop stepper motors

- dm542t stepper drivers

- old Desktop computer 
- parallel pci card 
- aluminium 6061 for gantry build 
- aaluminium extrusion size:6060 
- ballscrew 1605 and supports 
- contactors , mcbb and isolators 
- limit switches ,emergency stop and shielded wires

## Software

### Install LinuxCNC
- Download LinuxCNC ISO
- Flash to USB
- Install on PC
- Verify real-time latency (Mine had high latency so during execution steps might get missed so make sure you choose right pc or use an motion controller)

##### STEPCONF WIZARD CONFIGURATION: FOR INITIAL SETUP

- Select paraller port 
- choose pins for step/dir ,limit switches , estop and spindle 
- Calculate your steps per mm and enter it 
- enter velocity and accelearation
- enter microstepping value 

## MECHANICAL DESIGN:

- The mechanical structure was inspired by existing CNC CAD models available online
- Aluminium extrusion and 6061 plates(10MM-THICKNESS) were used for rigidity
- Ball screws were used on all three axes for  accuracy
- Some CAD reference models are attached for design understanding

## Electrical system :

- 230V AC,6A single-phase supply used as the main input power source
- 36V,12A SMPS used to power the stepper motor drivers (DM542T)
- Shielded motor cables used between drivers and stepper motors to reduce EMI and electrical noise
- 5V SMPS used to power the parallel port breakout board and control electronics
- MCBs used for overcurrent and short-circuit protection
- Contactors used for main power switching and emergency isolation
- Isolators used to safely disconnect power during maintenance

