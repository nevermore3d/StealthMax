[![Support Nevermore3D - Buy me a coffee](https://img.shields.io/badge/Support%20Nevermore3D%20-Buy%20me%20a%20coffee-orange.svg)](https://www.buymeacoffee.com/nevermore3d)

# StealthMax

A non-warp Nevermore Max Frame. Smaller, less parts/assembly, easier sourcing. Uses standard bolts, easily available GPU fan (BFB0712HF, Nevermore branded version [HERE](https://www.onetwo3d.co.uk/product/nevermore-bfb0712hf-65mm-fan/?wpam_id=2)(UK), [HERE](https://www.replimat.eu/nevermore-bfb0712hf-fan-65mm/rt10136)(DE) and [HERE](https://kb-3d.com/store/fans/983-nevermore-65mm-blower-cage-fan-for-stealthmax-1694204852771.html)(US). It also supports the [Sanyo C70](https://products.sanyodenki.com/en/sanace/dc/centrifugal-fan/9TD12P6G001/) (requires printing the casing pieces mirrored as it spins the opposite direction). <BR>Compared to the regular Max v2 beta, Stealthmax also adds an exhaust option (handy for keeping the chamber cool for PLA or PETG). The HEPA filter has moved into the center hub in order to shrink the overall size (now uses Xiaomi Mijia G1 130x40mm hepa filters).<BR><BR>
So far theres no official build guide, so please check out a) the CAD file that has every bolt, nook and cranny, b) the wiring guide on the [nevermore controller](https://github.com/SanaaHamel/nevermore-controller) github, and c) the [Nevermore Discord server](https://discord.gg/H8tZ9fZVQ4) for any additional questions regarding your build or software. 
![StealthMax](./StealthMax.png)
STLs exported. Check out the first version software bluetooth controller with klipper integration [@ SanaaHamel/nevermore-controller](https://github.com/SanaaHamel/nevermore-controller).

Special thanks to @SanaaHamel, @TubaToothpasties, @Blamm, @Backslash for all the help, nudges, support and additions to the project!

# Bill of Materials and Sourcing Guide
## Things to buy
This is a list of all the required parts. The links to items on this page are **affiliate links** that will share a few per cent of the sales price with the nevermore project at no additional cost to the user, we'd be thrilled if you use them! We do not, however, have any affiliations/contacts with the stores themselves, reach out if there are any bad experiences so we can remove such links.<br><br>Also, do feel free to source everything elsewhere to your custom desires, but before placing any orders, please make sure you covered the details for sourcing in the next section!<br><br> As a final - and most comfortable - sourcing route, feel free to try the awesome [Advanced Stealthmax Kit by OneTwo3d](https://www.onetwo3d.co.uk/product/nevermore-stealthmax-filter-kit/?wpam_id=2), containing everything needed for the stealthmax in one order, including two XL bags of Nevermore Carbon. A [Basic Stealthmax Kit](https://www.onetwo3d.co.uk/product/nevermore-stealthmax-filter-kit-basic/?wpam_id=2) without electronics is now also available.<br>
|                      | Amount                                            | Part                                                                                           | Source                                                                                                                                     |
| ----                 | ----:                                             | ----                                                                                           | :----:                                                                                                                                     |
| **Electronics**      |  1 pc                                             | DELTA BFB0712HF 65mm GPU fan                                                                   | [OneTwo3D](https://www.onetwo3d.co.uk/product/nevermore-bfb0712hf-65mm-fan/)                                                               |
|                      |  2 pcs                                            | BME280 *<sup>1</sup>*                                                                          | [AliExpress](https://s.click.aliexpress.com/e/_DCjWhgZ)                                                                                    |
|                      |  2 pcs                                            | SGP40 *<sup>2</sup>*                                                                           | [AliExpress](https://s.click.aliexpress.com/e/_DE5jOTT)                                                                                    |
|                      |  1 pc                                             | Mateksys 6-30V Buck Converter *<sup>3</sup>*                                                   | [AliExpress](https://s.click.aliexpress.com/e/_oEkrGWR)                                                                                    |
|                      |  1 pc                                             | Raspberry Pi Pico W *<sup>4</sup>*                                                             | [AliExpress](https://s.click.aliexpress.com/e/_okun5yX)                                                                                    |
| **Fasteners**        |  7 pcs                                            | M2x4 FHCS                                                                                      | [AliExpress](https://s.click.aliexpress.com/e/_Dd3ZxlT)                                                                                    |
|                      | 18 pcs<br>4 pcs                                   | M3x6 BHCS<br>M3x12 BHCS                                                                        | [AliExpress](https://s.click.aliexpress.com/e/_DduS2Vn)                                                                                    |
|                      | 2 pcs<br>4 pcs<br>7 pcs<br>1 pc<br>2 pcs<br>4 pcs | M3x8 SHCS<br>M3x10 SHCS *<sup>5</sup>*<br>M3x12 SHCS<br>M3x16 SHCS<br>M3x20 SHCS<br>M3x25 SHCS | [AliExpress](https://s.click.aliexpress.com/e/_DkxhzGZ)                                                                                    |
|                      |  1 pc                                             | M3 Hex Nut                                                                                     |                                                                                                                                            |
|                      | 24 pcs                                            | M3xD5.0xL4.0 Heat Set Inserts                                                                  | [AliExpress](https://s.click.aliexpress.com/e/_DeVF8rT)                                                                                    |
| **Filtration**       |  2 l                                              | Carbon                                                                                         | [Fabreeko](https://www.fabreeko.com/products/nevermore-carbon?variant=43205733482751)                                                      |
|                      |  2 pcs                                            | HEPA filters (for Xiaomi Mijia G1)                                                             | [AliExpress](https://s.click.aliexpress.com/e/_EGPsFBt)                                                                                    |
| **Fittings**         |  1 pc                                             | PC4-M10 Pneumatic Fitting                                                                      |                                                                                                                                            |
| **Sealing**          |  1 pc                                             | 250x3mm round acrylic panel *<sup>6</sup>*                                                     |                                                                                                                                            |
|                      |  1 m                                              | 3mm sponge cord *<sup>7</sup>*                                                                 | [AliExpress](https://s.click.aliexpress.com/e/_DCBnSol) (black)<br>*or*<br>[AliExpress](https://s.click.aliexpress.com/e/_DnnezK9) (white) |
| **Wiring**           |  1 pc                                             | M10 threaded DC connector                                                                      | [AliExpress](https://www.aliexpress.com/item/33001103693.html?spm=a2g0o.order_list.order_list_main.89.50ea1802RQAeZj)                      |
|                      |  1 pc                                             | pre-wired 6-pin 1.25mm pitch JST connector (1x Male, 1x Female)                                | [AliExpress](https://s.click.aliexpress.com/e/_mL6z69Y)                                                                                    |
|                      |  2 pcs                                            | pre-wired 4-pin 1.25mm pitch JST connector (1x Male, 1x Female)                                | [AliExpress](https://s.click.aliexpress.com/e/_mL6z69Y)                                                                                    |     
|                      |  1 pc                                             | JST-PH 4-pin male GPU fan connector                                                            | [AliExpress](https://s.click.aliexpress.com/e/_DklkchV)                                                                                    |
|                      |  30 cm                                            | AWG26 (0.14 mm²) cable *<sup>8</sup>*                                                          |                                                                                                                                            |
|                      |                                                   | Heat shrink tubing (for AWG26)                                                                 |                                                                                                                                            |


*<sup>1</sup>*  Temperature and humidity sensor in the correct dimensions (10.5mm * 13.5mm, single m3 bolt)<br>
*<sup>2</sup>*  VOC sensor in the correct dimensions (10.5mm * 13.5mm, single m3 bolt)<br>
*<sup>3</sup>*  Supplies 5 VDC to the Raspberry Pi Pico from the 12 VDC input<br>
*<sup>4</sup>*  The "W" version is needed for bluetooth printer communication, while the non-W needs to be connected by an additional physical USB connection (not yet supported in software). Pre-soldered pins recommended for increased simplicity for most users.<br>
*<sup>5</sup>*  Must use BHCS if using CPAP Tupe Intake<br>
*<sup>6</sup>*  May use 4mm thick panel, s. [Parametric Lid](Parametric_Lid_stealthmax.f3d)<br>
*<sup>7</sup>*  Shore A <=0<br>
*<sup>8</sup>*  25 cm between DC connector and buck converter and 5 cm between buck converter and fan connector

## Fasteners broken down
*Note:*<br>
*This list is missing fasteners for mounting of SGP40, BME280, Mateksys Buck Converter and the remaining connectors!*<br>
*A ball driver will be needed to install some of these.*<br>
- **7x M2x4 FHCS**
    - 3x Fan
    - 4x Raspberry Pi Pico
 
- **18x M3x6 BHCS**
    - 8x Main and Flow Chamber Connection
    - 6x Lid Latches *(may use SHCS)*
    - 2x Lid Front Hinge *(may use SHCS)*
    - 2x Basket Lid
   
- **4x M3x12 BHCS**
    - 4x Main and Flow Chamber Connection
 
- **2x M3x8 SHCS**
    - 2x Mounting
 
- **4x M3x10 SHCS**
    - 4x Mounting *(must use BHCS if using CPAP Tupe Intake)*
 
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

      ![StealthMax](./SM_PROMO_small.png)
      ![StealthMax](./SM_builds_small.png)
