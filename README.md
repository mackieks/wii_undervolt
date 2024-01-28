Adjustable regulator board for Wii undervolting testing. Solderpad Hardware License v2.1 
 
<img src="https://github.com/mackieks/wii_undervolt/blob/main/images/board.jpg" width=1200>

- 3.5 - 5.5V input
- x4 MUN3CAD03-SE 0.6-3.3V 3A buck regulators
- Trimpots for output voltage adjustment (feedback resistors pre-tuned for Wii undervolting)
- 4-terminal current sense resistors for input and outputs
- [Mouser project with BOM
](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=8f9d8d9514)
<img src="https://github.com/mackieks/wii_undervolt/blob/main/images/reg_board.png" width=1200>
<img src="https://github.com/mackieks/wii_undervolt/blob/main/images/reg_board2.png" width=1200>

Vin and each regulator output have dedicated 100-milliohm 4-terminal sense resistors. When powering a load from the reg board, you can measure across the resistors by poking your multimeter probes into the plated test pads. Multiply the voltage by 10 to get the load current in amps.

<img src="https://github.com/mackieks/wii_undervolt/blob/main/images/zoom.jpg" width=400> <img src="https://github.com/mackieks/wii_undervolt/blob/main/images/tool.jpg" width=600>
Each regulator has a trimpot for adjusting the voltage. Turn it clockwise to increase Vout, and counterclockwise to decrease Vout. You can turn the pots with tweezers or a tiny, blunt Phillips screwdriver.

**Note:** the trimpots are fragile mechanical devices. If you turn them too far in one direction, they'll 'wrap around' to the other side. When overturned like this, there's a small region that won't produce a reasonable resistance, causing Vout to collapse. Just keep turning and Vout will jump back to the intended range.
 

<img src="https://github.com/mackieks/wii_undervolt/blob/main/images/test.jpg" width=1200>

## Schematic
<img src="https://github.com/mackieks/wii_undervolt/blob/main/images/undervolt.png" width=1200>
