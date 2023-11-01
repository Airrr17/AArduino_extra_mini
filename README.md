# ATmega328p tqfp extra mini board. 
This comes where your code are perfect enough and you just need to pack your project tiny.  
AArduino extra mini.  
  
  
**Board version 0.9:**  
I just wanted to make a smaller board for this microcontroller.  
_Size is 12.5mm X 25.5mm only!_   
So here is minimal ATmega328p configuration. All pins are exposed for use.  
No voltage regulator, 5.0v maximum. rtfm.  
You can flash a bootloader after soldering the cpu, use SPI pins then.  
  
  

PCBway and JLpcb gerbers are provided.  
  
  
  
  Parts:  
- ATmega328p-au, TQFP.  
- 16mHz quartz, 5.0x3.2mm.  
- Some Rs, Cs and LEDs, 0805.  
- Programming pin header, 5 pins, P1.27.  
- Optional "left-first pin header" (or right) 2.00mm pitch.  
  
  
Soft:
No firmware, use arduino bootloader.  
  
  
Photos:  
[![click for full size](pics/schemS.png)](pics/schem.png)
![pic](pics/pcb.png)  
R1 - 1k  
R2 - 10k  
R3 - 1k  
Y1 - 16mHz  
C1 - 10u  
C2 - 100n  
C3 - 22pF  
C4 - 22pF  
C5 - 100n  
C6 - 100n  
D1 - any led  
D2 - any led  
U1 - ATmega328p tqfp OR ATmega48P/88P/168P tqfp  
  
![pic](pics/place.png)
![pic](pics/pcb_3d1.png)
  
   
   
Can be soldered with first-left (right) pin header 2.0mm:  
![pic](pics/pcb_3d2.png)
[![click for full size](pics/photo01s.jpg)](pics/photo01.jpg)
About the same photo. Male or female pin header. 1.27mm!:  
[![click for full size](pics/photo01s.jpg)](pics/photo01.jpg)
