
## The Scope 
In this repo i will show how i got access to the UART  interface even without the common  
set of exposed pins / test pads, using U-Boot to gain root on an early stage and eventually  
loading & dumping the firmware   


## Initial Recon  
Opening up the camera shows some  some obvious candidates for a straightforward  
UART access, there are 4 test pads in a row that seems to be the Tx Rx Ground and  
power, but testing it with a multimeter gave the wrong readings, i gave a few of them  
in the picture for some context 
![pcb](images/Initial_pcb.png)