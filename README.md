# Xiaomi-C200-Firmware-Analysis

## The Scope 
In this repo i will show how i got access to the UART  interface even without the common
set of exposed pins / test pads, using U-Boot to gain root on an early stage and eventually 
loading & dumping the firmware 
### Initial Recon
After opening up the camera, i was greeted with a PCB that seemed to have 
some obvious candidates for a straightforward UART access
![[Intial_pcb.png]]