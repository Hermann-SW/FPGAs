## 12/29/2020

My older son did register at Intel, and installed "Quartus Prime Lite Edition" for working with EP4CE10E22C8N altera fpga cyclone IV development board. Then he started from a binary counter demo (on the leds), used PLL divider 50 to get 1MHz clock, another divider by 1000 for 1KHz. The 1KHz clock is used to drive 4 digits from 7-segment display:  
![](https://raw.githubusercontent.com/Hermann-SW/FPGAs/main/res/out.anim.gif)


Oscilloscopy view on enable line of one digit, and on transistor triggering that. Since one digit gets updated at a time only, 1KHz reduces to 250Hz update frequency for the measured digit:  
![](https://raw.githubusercontent.com/Hermann-SW/FPGAs/main/res/bmp_9_000.jpg)


One key was connected to buzzer, this was single shot capture of keypress:  
![](https://raw.githubusercontent.com/Hermann-SW/FPGAs/main/res/bmp_9_002.jpg)
