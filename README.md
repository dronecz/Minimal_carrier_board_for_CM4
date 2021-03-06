# Minimal carrier board for Compute Module 4

This is based on design from [Prof. Fartsparkle´s](https://hackaday.io/project/175832-minimal-raspberry-pi-cm-4-carrier). I made it 2 layer board and changed slot for SD card. 

### Revisions:

- **rev.A**

This is just copy of the design from Timon. I just added 2x7 pin header and made shape of the board to the size of the Einsy board so I can use it for Octoprint. 

Board is tested and working. There is UART connection at that 2x7 pin header connected to the GPIO´s at CM4. There is slight problem with cables for HDMI and USB, but you ca solve that with righ cables.  

*WARNING* : The pinout for Einsy board is mirrored so I do not take any responsibility for damage which can be cause by this. You can change that in files and made your own board.

- **rev.B** **WARNING**

**UPDATE - 5/2/2021**

I ordered PCB´s and after assembly of one board, I did found out that camera connector colide with CM4 because it is to close. Please use **rev.C**, if you want to make boards!

---

I redesigned whole board and made it little bit bigger. Added 3.2mm mounting holes to each corner, added boot button for versions of CM4 with eMMC onboard (working), added connector for camera and added standard 40-pin header for Raspberry Pi.

I did not made this board yet but I did test distances between cables and rearanged them so they should not colide. Height of camera connector should be OK beneeth CM4, but this need to be tested. 

![](https://github.com/dronecz/Minimal_carrier_board_for_CM4/blob/main/images/img_A.png)


- **rev.B_alt**

This is same board as rev.B, but there are 22-pin connectors which are same as those used at official IO board. 

This version of the board was not yet manufactured.  

I have some rev.A boards which you can buy at my [Tindie](https://www.tindie.com/products/dronecz/minimal-carrier-board-for-compute-module-4/) store. 

- **rev.C**

Layout of the board is same with **rev.B** but I did move CM4 about 2 mm up and camera connector about 1 mm down. Half of the board was routed again. 

**This revision was not manufactured and it is not tested!** 

![](https://github.com/dronecz/Minimal_carrier_board_for_CM4/blob/main/images/img_rev_C_a.png)
