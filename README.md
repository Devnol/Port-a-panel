# Port-a-panel
A portable monitor enclosure using the AU Optronics B156XW04 panel and an aftermarket driver board

## The story
After getting a monitor for my desk I realised that having a dual monitor setup for my laptop is a no-brainer for any sort of productivity.
Since I'm a laptop guy and I travel or work away from home a lot I wanted to be able to have that luxury wherever I go. Looking around, portable monitors seemed to be out of my budget (starting from around 100$). I had a spare laptop panel laying around and I thought to myself: "Why not make my own portable monitor?". And so I did. I took apart an old HP Pavillion 15 and took out the panel. It's only 1366x768 and the viewing angles are pretty bad but it does the job. 
In this repo you can find all the 3D Models I made for the panel and the driver board, as well as some resources I used for reference. I'm not sure how useful this will be for other people but it can probably be adapted to fit other panels with little effort since I'm trying to make it as parametric as possible.

## Parts
- AU Optronics B156XW04 panel (I used a v5 pane from an HP Pavillion 15-b003ev)
- Driver board (make sure it's compatible with the panel and particular revision you have) I used [this one](https://www.ebay.com/itm/384518789920) from ebay which has VGA, HDMI, RCA and USB media inputs as well as an analog TV tuner which I won't be using.
- 12x12mm heatsink or similar for the driver board IC (optional)
- Assorted screws (TBD)
- Magnets (TBD)

## Included parts
3D models in f3d form to be imported into Autodesk Fusion are available in [Models](/Models):
- Driver\_Board: Set of rough silhouettes for the pcbs of the driver board Contains 3 distinct Components:
	- Mainboard: The driver board itself
	- Controller: A daughter board with tact switches for controlling the OSD
	- Receiver: A daughter board with an IR receiver for the TV remote and a power LED
- Panel\_Physical: A 3D model of the actual panel based on the datasheet, used to create a negative for the 3d printed shell and as a size reference.
- Driver\_Enclosure: Casing for the display driver control board
- Panel\_Enclosure: The actual frame of the monitor itself

Other resources such as images, drawings, pdfs etc. can be found under [Resources](/Resources)

## External Resources
- Inspiration from this project came mostly from some of DIY Perks' videos, you should definitely check out his channel, he makes some insane projects.
	This project is very loosely based on
	- [Triple-Screen Laptop DONE RIGHT!](https://www.youtube.com/watch?v=aUKpY0o5tMo)
	- [Build a DIY screen out of recycled parts of cheap](https://www.youtube.com/watch?v=CfirQC99xPc)
- Also consulted the Datasheet for the panel which I found [here](https://datasheetspdf.com/datasheet/B156XW04-V5.html). Also available in this repo as [B156XW04-V5-datasheet.pdf](/Resources/B156XW04-V5-datasheet.pdf)

## License
This project is licensed under the WTFPL license because honestly you should just do whatever you want with it. I made this for myself and you're more than welcome to download and edit this for your own use.
