# Introduction #

This shield should fit any of the Arduino boards or clones. It has been tested with the "Duemilanove", which is a handy choice since it has a built-in USB connector for data logging.  You can find the Arduino and its clones many places, including [Modern Devices](http://www.moderndevice.com) and [Sparkfun](http://www.sparkfun.com).  Typical cost is around $30.

# Details #

  * 4-channel ADC chip: MCP3424 I2C
  * ambient temperature sensor MCP9800
  * 2 DC voltage outputs with hardware PWM for driving SSR

**Assembly examples. Add your links here**

http://bvwelch.com/?page_id=40

**Parts list:**

  * **Arduino or clone $30 + shipping**
  * **PCB from Jim. $6 + shipping.** [Click here](http://www.mlgp-llc.com/arduino/public/arduino-pcb.html) for link.

Note: If Mouser or Digikey are out of stock, you might try this search engine: [OctoPart](http://octopart.com/parts/search?q=MCP3424-E/SL)

| **Qty** | **Item** | **Mouser** | **Digikey**| **Price (each)** | **Notes** |
|:--------|:---------|:-----------|:-----------|:-----------------|:----------|
| 1       | MCP3424 (SMD) | 579-MCP3424-E/SL |  MCP3424-E/SL-ND |   $4.26          | note 7    |
|1        | MCP9800 (SMD) |579-MCP9800A0T-M/OT | MCP9800A0T-MOTGCT-ND |  $1.76           |           |
| 6       | Phoenix MPT2 screw term. | 651-1725656 | 277-1273-ND | $1.11            | note 9    |
| 2       | 8-pin male header | 538-22-28-4085 | WM6408-ND  | $0.54            | note 1,2,8 |
| 2       | 6-pin male header | 538-22-28-4065 | WM6406-ND  | $0.46            | note 1,2,8 |
| 2       | 2N3904 NPN transistor | 610-2N3904 | 2N3904FS-ND | $0.42            | note 3,4  |
| 2       | 4.7K ohm resistor, 1/8W | 270-4.7K-RC | RNF1/8T14.75KFRCT-ND | $0.15            | note 4,6  |
| 2       | 5.6K ohm resistor, 1/8W | 270-5.6K-RC | RNF1/8T15.36KFRCT-ND | $0.15            | note 4,6  |
| 1       | 1N4148 diode | 512-1N4148 | 1N4148TACT-ND | $0.14            | note 4    |
| 1       | 10 uF electrolytic capacitor | 647-UVR1C100MDD1TD | 493-1372-ND| $0.24            | note 4    |
| 2       | 0.1 uF ceramic capacitor | 594-K104Z15Y5VF5TL2 | BC1160CT-ND (min 10)| $0.066           | note 4    |
| 1       | Breakaway header | 538-22-28-4085 | WM6408-ND  | $0.54            | note 5    |

**Notes**
  1. Use 'stackable' headers, for example Sparkfun PRT-09280 and PRT-09279 if you want to stack another shield on top of this one
  1. Or you could buy a 28-pin Mouser 538-22-28-4285 and cut apart to make your own 6-pin and 8-pin headers.
  1. Almost any NPN transistor will work here (2N2222, BC547 for instance)
  1. Probably available locally at Radio Shack, etc.
  1. Break apart to make all of the two-pin headers
  1. Resistor values are not critical, but check sizes.  Hole spacing on PCB is only 7mm.
  1. MCP3424 currently on backorder at Mouser. Try [OctoPart](http://octopart.com/parts/search?q=MCP3424-E/SL)
  1. Male headers mounted to point downward, below board, to engage Arduino female sockets.
  1. Tyco makes a less expensive, but still good quality terminal, priced at $0.65 ea at Digikey (item no. A98333-ND)


---

