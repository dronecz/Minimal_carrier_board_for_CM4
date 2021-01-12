# Minimal carrier board for Compute Module 4

This is based on design from [Prof. Fartsparkle´s](https://hackaday.io/project/175832-minimal-raspberry-pi-cm-4-carrier). I made it 2 layer board and changed slot for SD card. 

### Revisions:

- **rev.A**

This is just copy of the design from Timon. I just added 2x7 pin header and made shape of the board to the size of the Einsy board so I can use it for Octoprint. 

Board is tested and working. There is UART connection at that 2x7 pin header connected to the GPIO´s at CM4. There is slight problem with cables for HDMI and USB, but you ca solve that with righ cables.  

*WARNING* : The pinout for Einsy board is mirrored so I do not take any responsibility for damage which can be cause by this. You can change that in files and made your own board.

- **rev.B**

I redesigned whole board and made it little bit bigger. Added 3.2mm mounting holes to each corner, added boot button for versions of CM4 with eMMC onboard (**untested**) and added standard 40-pin header for Raspberry Pi.

I added connectors for camera and DSI display, but later realize that they are in size which are used at Raspberry Pi Zero so if you want to use this feature, please bare that in mind. 

I did not made this board yet but I did test distances between cables and rearanged them so they should not colide. 

I have some rev.A boards so if there is demand, I will probably sell them in my Tindie store. 
