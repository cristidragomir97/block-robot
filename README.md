# blockRobot

![](https://i.ibb.co/tB3JZtd/front.png)
## Bill-of-materials 

| Part |Units | Cost |
|------|------|-------|
|  [75:1 Pololu Gearmotor](https://www.tme.eu/ro/en/details/pololu-3074/dc-motors/pololu/75-1-hpcb-6v-dual-shaft/#)  |  2   | 40.60$ |
|  [Hall Encoders](https://www.tme.eu/ro/en/details/pololu-4760/accessories-for-micromotors/pololu/magnetic-encoder-12-cpr-2-7-18v-4760/)  |  1   |  15.86$  |
| [Track Set](https://www.tme.eu/ro/en/details/pololu-3033/accessories-for-robotics-and-rc/pololu/30t-track-set-black/)    |   1   |   15.61$   |
[Arduino Pro Mini](https://www.robotshop.com/eu/en/pro-mini-arduino-microcontroller.html)    |   1  |   10.74$  |      |
|  [Motor Driver](https://www.tme.eu/ro/en/details/pololu-713/motor-control-modules/pololu/)    |  1    |  5.35$    | 
| [Step-up Regulator](https://www.robotshop.com/eu/en/pololu-5v-step-up-voltage-regulator-u3v70f5.html)   |   1   |  23.75     | 
|  [Battery Charger](https://www.tme.eu/ro/en/details/oky3404/charger-modules/okystar/)   |  1    | 2.30$      | 
|     |  Total    |  **112.21$**     | 

Additionally, for a fully functional robot, you will need a SBC and a rechargeable battery. 

### Batteries
block-robot is designed to use a single 3.7V Li-Po/Li-Ion cell (or multiple balanced cells in parallel). That gives us a few different options:

#### 18650 Cells 
These are kind of a larger version of the AA batteries, that are rated for 3.7V. They range from 2000mAH to 3500mAh, and you can connect them in parallel as long as all batteries have been fully charged. 

These batteries are often used for vapes and e-cigarettes, so if you cannot find them at a local electronics store, you might be able to find them at vape shops.

You can also find them in packs like [these](https://shop.pimoroni.com/products/lithium-ion-battery-pack?variant=23417820487). 
![](https://hallroad.org/images/detailed/11/10pcs-lot-18650-rechargeable-battery-2600mah-3-7v-isr18650-li-ion-rechargeable-batteries.jpg)
#### LiPo Packs
thttps://www.tme.eu/ro/en/details/accu-lp123497_cl/rechargeable-batteries/cellevia-batteries/ 


**Pro tip:** USB Powerbanks tend be way cheaper than any of the options above. Plus, you can find them everywhere. Inside every power-bank there is a Li-Po cell waiting for a new life, you just need to crack that case open.

## Parts

### Platform

### Bricks

### Adapters

#### Raspberry Pi 4 Case

#### Raspberry Pi Camera


## Electronics
![](https://i.ibb.co/fStdTbV/ass.png)
### Power Delivery
* **TP4056** Battery charger
* **U3V70F5** 5V Step-Up Power Regulator


### Motor Control
* **Arduino Pro Mini 8Mhz**
* **TB6612FNG** Motor Driver


