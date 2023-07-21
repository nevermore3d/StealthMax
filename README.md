# StealthMax

A non-warp Nevermore Max Frame. Smaller, less parts/assembly, easier sourcing. Uses standard bolts, easily available GPU fan (BFB0712HF, Nevermore branded version here: https://www.onetwo3d.co.uk/product/nevermore-bfb0712hf-65mm-fan/), and adds an optional exhaust option. The HEPA filter has moved into the center hub in order to shrink the overall size (now uses Xiaomi Mijia G1 130x40mm hepa filters).
![StealthMax](./StealthMax.png)
STLs exported. Check out the first version software bluetooth controller with klipper integration [@ SanaaHamel/nevermore-controller](https://github.com/SanaaHamel/nevermore-controller).

Special thanks to @SanaaHamel, @TubaToothpasties, @Blamm, @Backslash for all the help, nudges, support and additions to the project!

## Electronics links
2 x [SPG40](https://s.click.aliexpress.com/e/_DE5jOTT) sensor in the correct dimensions

2 x [BME280](https://s.click.aliexpress.com/e/_DCjWhgZ) Temp/Humidity sensor in the correct dimensions 

1x [Mateksys 6-30V Buck Converter](https://s.click.aliexpress.com/e/_oEkrGWR) (Supplies 5v to the pico from the 12v dc input)

1M x [BLACK](https://s.click.aliexpress.com/e/_DCBnSol) **OR** [WHITE](https://s.click.aliexpress.com/e/_DnnezK9)) 3MM foam cord seal, shore A <=0.

## Nuts and Bolts
*Note:*<br>
*This list is missing screws for mounting of SGP40, BME280, Mateksys Buck Converter and the remaining connectors!*<br>
*A ball driver will be needed to install some of these.*<br>
 
- **7x M2x4 FHCS**
    - 3x Fan
    - 4x RPi PICO
 
- **10x M3x6 BHCS**
    - 8x Main and Flow Chamber Connection
    - 2x Basket Lid
 
- **4x M3x12 BHCS**
    - 4x Main and Flow Chamber Connection
 
- **8x M3x6 SHCS**
    - 6x Lid Latches
    - 2x Lid Front Hinge
 
- **2x M3x8 SHCS**
    - 2x Mounting
 
- **4x M3x10 SHCS**
    - 4x Mounting
 
- **7x M3x12 SHCS**
    - 7x Mounting
 
- **1x M3x16 SHCS**
    - 1x Air Exhaust Wheel
 
- **2x M3x20 SHCS**
    - 2x Mounting
 
- **4x M3x25 SHCS**
    - 2x Lid Front Hinge
    - 2x Mounting
 
- **1x M3 Hex Nut**
    - 1x Sensor Latch

- **24x M3x5x4 Heat Set Insert**
    - 12x Flow Chamber
    - 6x Main Chamber
    - 2x Basket
    - 2x Lid Front Hinge
    - 2x Mounting

## Electronics & Wiring
- 1x Raspberry Pi Pico W
- 2x SGP40 sensors (small kind, single m3)
- 2x BME280 sensors (small kind, single m3)
- 1x Mateksys 6-30V voltage regulator
- 1x M10 threaded DC connector
- 1x pre-wired 6-pin 1.25mm pitch JST connector (1x Male, 1x Female)
- 2x pre-wired 4-pin 1.25mm pitch JST connector (1x Male, 1x Female)
- 1x JST-PH 4-pin male GPU fan connector
- 30cm AWG26 (0.14mm²) cable (12V/GND), of which 25cm between DC connector and Mateksys, and 5cm between Mateksys and fan connector
- 1x 65mm GPU fan (BFB0712HF)

## Extras
- 1x 250mm round acrylic sheet, 3mm thick (or 4mm thick, s. [Parametric Lid](Parametric_Lid_stealthmax.f3d))
- 1 meter of 3mm foam cord (neoprene or silicone foam cord works well, shore a <=0, shore 00 <=50. 
- 1x Pneumatic Bowden Fitting M10
- 2x HEPA filters (130x40 mm, same as Xiaomi Mijia G1)
- Heat shrink tubing suitable for AWG26/28
