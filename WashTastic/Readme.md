# WashTastic



<img src="./pics/Assembled.jpg" width="350"> <img src="./pics/WashTastic Diagram V0.3.png" width="600">

<img src="./pics/top.png" width="350"><img src="./pics/bottom.png" width="350">
<img src="./pics/top_layout.png" width="350"><img src="./pics/bottom_layout.png" width="350">
<img src="./pics/Schematic_1W-meshtastic-node.png" width="500">

<img src="./pics/capacitor_orientation.png" width="200"><img src="./pics/diode_orientation.png" width="200"><img src="./pics/ic_orientation.png" width="200">

Make sure these components are oriented like the image shows :)
To rotate first left click then right click and rotate

if ordering from jlcpcb or pcbway the only component u need to get is promicro nrf52

### power consumption 

I used an ina3221 to measure the current usage over an hour and it came to about 20mAh. so by that calculations its using about 480mAh per day.

If u have better and real world data i will happily accept them :)

### firmware 

U need to flash the promicro with promicro diy Variant from the flasher.
U might need to update the bootloader of the promicro to get it to accept the firmware.
### stuff u need

[promicro NRF52840](https://vi.aliexpress.com/item/1005007040333351.html)




[Gerber](./Gerber_WashTastic-1W-meshtastic-nodezip.zip)

[BOM](./BOM_WashTastic-1W-meshtastic-node_V0.2.csv)

[PnP](./PickAndPlace_WashTastic-1W-meshtastic-node_V0.2.csv)

# To-do 

[]add ina if possible

[]uart pads for gps

[]groove on the bottom of the pcb

[]through holes for power?

[]increase 5v boost to 5.5v?

