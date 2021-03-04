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
SN74AHC86|14-DIP|U1|1|DigiKey|296-4627-5-ND
SN74AHC574|20-DIP|U2,U3|2|DigiKey|296-4616-5-ND
LD1117AV33|TO-220-3|U4|1|DigiKey|497-1485-5-ND
SN74HC266|14-DIP|U5|1|DigiKey|296-8294-5-ND
0.1uF Ceramic Capacitor|Radial|C1-3,5|4|DigiKey|399-14065-1-ND
10uF Ceramic Capacitor|Radial|C4|1|DigiKey|445-181284-1-ND
40 Position Female Header|-|J1|1|DigiKey|S6104-ND
3x1 Male Header|-|JP1|1|DigiKey|732-5316-ND
2x1 Male Header|-|J2|1|DigiKey|732-5315-ND
Jumper|-|JP1|1|DigiKey|609-6251-ND
14-DIP Socket|14-DIP|U1,4|2|DigiKey|AE9989-ND
20-DIP Socket|20-DIP|U2-3|2|DigiKey|AE9998-ND
