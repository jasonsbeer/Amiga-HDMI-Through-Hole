# Amiga Video Slot to HDMI with Through Hole Components
This project was inspired by the [Amiga Digital Video](https://github.com/c0pperdragon/Amiga-Digital-Video) project by c0pperdragon. This design makes use of the Amiga 2000/3000 video slot. I beleive in simplicity. This project installs in the Amiga video slot and makes use of easy to solder through hole components, making it friendly to even the novice DIYer. All the components are currently available through DigiKey, meaning they are readily available and easy to obtain.

![Video Card Image](Amiga-Card-Thru-Hole.png)

## PCB Ordering
The gerber files are available in the [Gerber](/Gerber) folder. Download the file and send to your preferred PCB manufacturer. I've been ordering mine through PLCPCB and am very happy. Most of the options will be set directly from the Gerber file. For the rest, you can select these [options](JLCPCB.png).

## PCB Assembly
Order parts from the BOM list. I have included DigiKey part numbers for reference. Solder the components to the board, noting orientation of the sockets. You can solder the chips directly to the board, but I do not recommend this for DIY projects.

### BOM
|Component|Package|Location|QTY|Source|Part Number|
--- | --- | --- | --- | --- | ---
LD1117AV33|TO-220-3|U1|1|DigiKey|[497-1485-5-ND](https://www.digikey.com/en/products/detail/stmicroelectronics/LD1117AV33/586006)

