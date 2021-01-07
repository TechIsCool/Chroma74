## Chroma74 Notes

DisplayData
Chroma74
JM10201828B
FCC ID: VC7120-0157
IC: 8910A - 1200157
61-74000200

https://fccid.io/VC7

#### Display

**NOTE:** The QR Code decodes to the the same as the first two lines

WF0750T80BF190E42U59S0
706697470-Y05J
WUXI VISION PEAK TECHNOLOGY
WFD0750BF19
JD

#### Board

DISPLAYDATA LTD 2016
EDK293 Issue 2
220-0083-02
EC243951

##### Exposed Pads

| Pad      | Pin  | Chip  | Name    | Notes                    |
| -------- | ---- | ----- | ------- | ------------------------ |
| TP2,TP12 | 31   | CC    | RESET_N | Reset Active Low (reset) |
| TP3,TP13 | 15   | CC    | P2_1    | D I/O Port 2.1, (debug)  |
| TP4,TP14 | VCC  | VCC   | VCC     |                          |
| TP5,TP15 | 16   | CC    | P2_2    | D I/O Port 2.2 (clock)   |
| TP6,TP16 | 6    | CC    | P0_1    | D I/O Port 0.1           |
| TP7,TP17 | 33   | CC    | P1_6    | D I/O Port 1.6           |
| TP8,TP18 | GND  | GND   | GND     |                          |
| TP9,TP19 | 32   |       | P1_7    | D I/O Port 1.7           |
| TP10     |      | E_INK |         |                          |
| TP11     |      | E_INK |         |                          |

#### CC1110Fx

Voltage Range: 2.0v - 3.6v

**NOTE**: All Digital I/O Test Pads are not connected to loads

#### Batteries

6x CR2450
3.2v - 1.8v
680mAh

Series Parallel 2x3
9.6v - 5.4v per string
2Ah

```
yes - these modern price tags are worth considering.  It is ... with me 
 recently a treaded run to (do not know if this is about the 
 dynamically increased price was angry customer) and curiosity got me 
 let's have a look.
 A dream for the purist - hardly a handful of components:
 six lithium button cells, according to the manufacturer with 2-3 accesses per day 
 a store from Macronix should last for five years
 MX25V8006EM1I-13G MX25U Series 3.6 V 8 Mb (8 M x 1/4 M x 2),
 e.paper-display from Wuxi Vision Peak Technology Corporation Limited with 
 around 7 "and probably 640 x 384 points and from Texas Instruments 
 Processor CC1110F32 Sub-1 GHz wireless MCU with up to 32 kB flash memory

 If I read correctly, the chip will send 315, 433, 868, or 
 915 MHz and also has USB on board.  - that gives space for ideas ...

 The manufacturer displaydata controls the parts via its own 
 Radio router, the labels should work bidirectionally and can 
 be several thousand in one system.

 greeting
```



## Links

https://github.com/donnm/rfcat

https://hackaday.com/2019/02/25/e-ink-price-tags-fall-off-store-shelves-onto-your-workbench/

https://www.npmjs.com/package/subgrfspy

https://getrileylink.org/product-category/rileylink-parts

https://github.com/ecc1/cc111x

https://webthesis.biblio.polito.it/8459/1/tesi.pdf

https://www.jemrf.com/collections/rf-sensors/products/wireless-base-station-for-raspberry-pi

https://hackaday.io/project/175947-74-e-ink-shelf-label-used-as-a-weather-station/details

https://github.com/atc1441/E-Paper_Pricetags