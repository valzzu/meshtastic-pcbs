# WashTastic

<img src="./pics/Assembled.jpg" width="350"> <img src="./pics/WashTastic Diagram V0.3.png" width="600">

<img src="./pics/top.png" width="350"><img src="./pics/bottom.png" width="350">
<img src="./pics/top_layout.png" width="350"><img src="./pics/bottom_layout.png" width="350">
<img src="./pics/Schematic_1W-meshtastic-node.png" width="500">

if ordering from jlcpcb or pcbway the only component u need to get is promicro nrf52

### power consumption

I used an ina3221 to measure the current usage over an hour and it came to about 20mAh. so by that calculations its using about 480mAh per day.

If u have better and real world data i will happily accept them :)

### firmware

U need to flash the promicro with promicro diy Variant from the flasher.

U might need to update the bootloader of the promicro to get it to accept the firmware.

If it doesent have a bootloader check [here](https://github.com/gargomoma/fakeTec_pcb?tab=readme-ov-file#my-promicro-is-dead-what-can-i-do)

### stuff u need

[promicro NRF52840](https://vi.aliexpress.com/item/1005007040333351.html)

[Gerber](./Gerber_1W-meshtastic-node_PCB_1W-meshtastic-node-0.3.3b.zip)

[BOM with connectors](./BOM_1W-meshtastic-node_0.3.3_connectors.csv)

or

[BOM without connectors](./BOM_1W-meshtastic-node_0.3.3_no-connectors.csv)

[PnP](./PickAndPlace_PCB_1W-meshtastic-node-0.3.3.csv)

## V0.3.5

the only major change in this version is the solar chargin ic is changed to CN3791.

Not tested but should work :)

It has input range of 4.5-28V.

<img src="./pics/V0.3.5/top_V0.3.5.png" width="350"><img src="./pics/V0.3.5/bottom_V0.3.5.png" width="350">
<img src="./pics/V0.3.5/top_layout_V0.3.5.png" width="350"><img src="./pics/V0.3.5/bottom_layout_V0.3.5.png" width="350">
<img src="./pics/V0.3.5/1. Main.png" width="500"><img src="./pics/V0.3.5/2. Solar.png" width="500">

JLCPCB is saying that the part is not selected nor does it allow to choose a replacement part, if that happens this is the part
[XR1365-680M](https://www.lcsc.com/product-detail/Power-Inductors_XR-XR1365-680M_C41384054.html?s_z=n_C41384054)
JLCPCB doesen't seem to have this part at all, rather it finds this part that is no where what the original was.
[XR1265-680M](https://jlcpcb.com/partdetail/Xr-XR1265680M/C5339474)

[promicro NRF52840](https://vi.aliexpress.com/item/1005007040333351.html)

[Gerber](./V0.3.5/Gerber_1W-meshtastic-node_PCB_1W-meshtastic-node-0.3.5.zip)

[BOM with connectors](./V0.3.5/BOM_1W-meshtastic-node_0.3.5_connectors.csv)

or

[BOM without connectors](./V0.3.5/BOM_1W-meshtastic-node_0.3.5_no-connectors.csv)

if u want BME280 use one of these.
also this results in extra charges since u need to use standard PCBA instead of economy.

[BOM with connectors](./V0.3.5/BOM_1W-meshtastic-node_0.3.5_connectors_BME280.csv)

or

[BOM without connectors](./V0.3.5/BOM_1W-meshtastic-node_0.3.5_no-connectors_BME280.csv)

[PnP](./V0.3.5/PickAndPlace_PCB_1W-meshtastic-node-0.3.5.csv)

> [!CAUTION]
> V0.4 has not been tested so order it at ur own risk!

In v0.4 nrf52840 is directly integrated on the pcb along with ina3221.
So no need to buy promicros.
In theory, it should just work but who knows 😅

I also added pins for gps since there was space.
plus the PCB is now 4 layers and there are very tiny vias so there's a possibility of extra charge.

u may also need to flash the nrf52 chip with a bootloader.

[Gerber v0.4](./V0.4/Gerber_1W-meshtastic-node_PCB_1W-meshtastic-node-0.4.zip)

[BOM v0.4 with connectors](./V0.4/BOM_1W-meshtastic-node_0.4_connectors.csv)

or

[BOM v0.4 without connectors](./V0.4/BOM_1W-meshtastic-node_0.4_no-connectors.csv)

[PnP v0.4](./V0.4/PickAndPlace_PCB_WashTastic-1W-meshtastic-node_V0.4.csv)
