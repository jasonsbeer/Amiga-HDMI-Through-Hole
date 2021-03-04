# Amiga Video Slot to HDMI with Through Hole Components
This project was inspired by the [Amiga Digital Video](https://github.com/c0pperdragon/Amiga-Digital-Video) project by c0pperdragon. This design makes use of the Amiga 2000/3000 video slot. I beleive in simplicity. This project installs in the Amiga video slot and makes use of easy to solder through hole components, making it friendly to even the novice DIYer. All the components are currently available through DigiKey, meaning they are easy to obtain.

![Video Card Image](Amiga-Card-Thru-Hole.png)

## PCB Ordering
The gerber files are available in the [Gerber](/Gerber) folder. Download the file and send to your preferred PCB manufacturer. I've been ordering mine through PLCPCB and am very happy. Most of the options will be set directly from the Gerber file. For the rest, you can select these [options](JLCPCB.png).

## PCB Assembly
Order parts from the BOM list. I have included DigiKey part numbers for reference. Solder the components to the board, noting orientation of the sockets. You can solder the chips directly to the board, but I do not recommend this for DIY projects.

### BOM
|Component|Package|Location|QTY|Source|Part Number|
--- | --- | --- | --- | --- | ---
4Mx16 DRAM|TSOP(II)| U6 | 1 | Ali Express or E-Bay| K4E641612D or GM71VS65163
