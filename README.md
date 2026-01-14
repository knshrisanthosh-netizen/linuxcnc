# linuxcnc



DIY CNC VMC using linuxcnc

In this project I built a three axis cnc vmc using linuxcnc with parellel port to understand how cnc works from ground up.
Material  used : 
1.MACH3 parallel port break out boaed
2.Nema 23 open loop stepper motors
3.dm542t stepper drivers 
4.old Desktop computer 
5.parallel pci card 
6.aluminium 6061 for gantry build 
7.aaluminium extrusion size:6060 
8.ballscrew 1605 and supports 
9.contactors , mcbb and isolators 
10.limit switches ,emergency stop and shielded wires

I did some succesful test with my diy cnc . i have attached my connections photo , cnc build photos and testing videos . spindle was not designed and so i tested out with marker as tool

The mechanical design was inspired from already existed cad models in internet.I have attached some  cad model


Install LinuxCNC
2.Download LinuxCNC ISO
3Flash to USB
4.Install on PC
5.Verify real-time latency 

STEPCONF WIZARD CONFIGURATION: FOR INITIAL SETUP

1.Select paraller port 
2.choose pins for step/dir ,limit switches , estop and spindle 
3.Calculate your steps per mm and enter it 
4.enter velocity and accelearation
5.enter microstepping value 




