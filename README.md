### canj

The canj is a small pcb designed to be smaller and cheaper than the [ThriftyBot CanJunction](https://www.thethriftybot.com/products/canjunction).

- 0.5" by 1.0"
- Solder pads
- $1.63 if parts bought in bulk
- VHB/ DualLock mounting

[Parts used](https://www.digikey.com/en/mylists/list/JSPG6NDKLX).

I recommend using [Oshpark](oshpark.com), as a board of this size is only $7.50 for 9 boards, tax & shipping included anywhere.
If Oshpark won't work, there are many other manufacturers like LCSC, PCBway and MacroFab.

Shipping from Digikey is not free, so make sure to combine orders if you have multiple to pay less.

##Instructions

Solder a 120 ohm 1206 SMD resistor to the side marked 'R'
Bridge the pads marked 'B'
Place the switch, with proper pin orientation to pin 1 and the silkscreen 'E' from the body of the switch
Solder the switch.
Connect CAN wires
The side marked 'R' should be on the side the bus coming from the direction of the systemcore/rio.
Do not wire the 'B' side to the systemcore/rio or it will not work.
