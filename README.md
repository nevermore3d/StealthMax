# StealthMax

A non-warp Nevermore Max Frame. Smaller, less parts/assembly, easier sourcing. Uses standard bolts, easily available GPU fan (BFB0712HF, Nevermore branded version here: https://www.onetwo3d.co.uk/product/nevermore-bfb0712hf-65mm-fan/), and adds an optional exhaust option. The HEPA filter has moved into the center hub in order to shrink the overall size (now uses Xiaomi Mijia G1 130x40mm hepa filters).
![StealthMax](./StealthMax.png)
STLs exported. Check out the first version software bluetooth controller with klipper integration [@ SanaaHamel/nevermore-controller](https://github.com/SanaaHamel/nevermore-controller).

Special thanks to @SanaaHamel, @TubaToothpasties, @Blamm, @Backslash for all the help, nudges, support and additions to the project!

## Nuts and Bolts
- 7x M2x4mm Flatheads (<=0.8mm head height, but not too wide as to avoid interfering with pico pins)
- 18x M3x6mm BHCS (ball driver will be needed to install a few of these, as straight-down access is not always possible)
- 2x M3x8mm BHCS (could possibly be m3x6 with plenty of loctite; for the main lid latch)
- 5x M3x10mm BHCS or SHCS
- 11x M3x12mm BHCS (7 of these are made for SHCS, but bhcs will work for easier sourcing)
- 1x m3x16
- 6x M3x25mm SHCS
- 1x M3 Hex Nut
- 24x Heat Inserts

## Electronics & Wiring
- 1x Raspberry Pi Pico W
- 2x SPG40 sensors (small kind, single m3)
- 2x BME280 sensors (small kind, single m3)
- 1x Mateksys 6-30V voltage regulator
- 1x M10 threaded DC connector
- 1x pre-wired 6-pin 1.25mm pitch JST connector (1x Male, 1x Female)
- 2x pre-wired 4-pin 1.25mm pitch JST connector (1x Male, 1x Female)
- 1x JST-PH 4-pin male GPU fan connector
- 30cm AWG26 cable (12V/GND), of which 25cm between DC connector and Mateksys, and 5cm between Mateksys and fan connector
- 1x 65mm GPU fan

## Extras
- 1x 250mm round acrylic sheet, 3 or 4mm thick
- 1 meter of 3mm foam cord (neoprene or silicone foam cord works well, shore a <=0, shore 00 <=50. 
- 1x Pneumatic Bowden Fitting M10
- 2x HEPA filters (130x40 mm, same as Xiaomi Mijia G1)
- Heat shrink tubing suitable for AWG26/28


