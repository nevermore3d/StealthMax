# Direct On Panel Mount (DOPM) instructions

![Direct On Panel Mount Front](/assets/renders/dopm1.png)

![Direct On Panel Mount Below](/assets/renders/dopm2.png)

If you don't have a Voron panel cutout, or want to mount a StealthMax on a different panel/surface, follow the instructions below for Direct On Panel Mount (DOPM).

Use the [Print Guide](https://bit.ly/NevermoreStealthMaxPrintGuide) to get a list of the printed parts you need for DOPM. They replace the files with the same numbers from the regular STL directory.

- **NOTE:** The exhaust will blow air straight out with some speed. You don't want this to happen right above the center of your bed for certain filaments, so position with care.
- A suggestion is to align the exhaust along the edge of the panel. For example, if the StealthMax is positioned on the top panel, position the exhaust near the front, not the center. 
- On a printer with a moving bed, the exhaust could be positioned on a side panel just below gantry to act as a part cooling accessory fan. 
- A third option, for users who look to optionally keep the chamber cool without cumbersome panel removal (for more harmless filaments in ventilated spaces), is to use the top mount position. This enables you to optionally remove the cartridge and exhaust up to 40CFM to keep the chamber ambient temperature.

## Tools needed
- A drill.
- A [40mm hole saw](https://s.click.aliexpress.com/e/_oEo5amR).
- A [3mm drill bit](https://s.click.aliexpress.com/e/_onEwfxl). 
- (Optional) A 2mm one to pre-drill for the hole saw. This can help but is not an absolute prerequisite.

## Drilling instructions
* The new 2-Flow chamber comes with print-in-place drill guides. Place the Flow Chamber on the panel of choice and tape it down securely.
* Drill 8 3mm holes in the locations marked with red circles below, using the flow chamber piece itself as your printed drill guide.
  * For the 5 holes where the 40mm cutouts will be, drill in the center of the cross pieces, through the panel below.
    * Optional: use a marker to mark these holes on the panel below, so you can be sure to drill the 40mm holes in the correct locations in the next step.
  * For the 3 holes around the 40mm exhaust cutout, use the 3.4mm holes to drill through the panel below. Don't worry about expanding the printed holes slightly, it won't matter.

![Direct On Panel Mount 3mm hole locations](/assets/docs/DOPM/dopm_3mm_hole_locations.png)

* Once you have drilled the 8 holes in the exact right spots, remove the Flow Chamber from the panel. Use the 40mm hole saw to drill out the 5 40mm holes in the panel. These holes will serve as air intakes/exhaust and as the mounting screws for the StealthMax on the panel.
* Verify that the printed 40mm screws will fit through the 5 holes you just drilled (and that they cover any rough edges that may be left).

  **NOTE:** Compared to the regular BOM, this installation **requires an additional heat-set insert** on the back side of the flow chamber, below the center exhaust. It also requires **an additional M3x10** screw. You can use an M3x12 screw, but then the main chamber side corresponding bolts need to be 10mm instead of 12. The two M3x25 screws that normally mount to the StealthMax to an extrusion will likely be a a bit short (with only 2mm extending through a 3mm panel). Switch to M3x28 screws instead. You can shorten a M3x30 screw, or use the 3mm drill to make sure the two M3x30 screws don't bottom out in the chamber-exhaust part.

  **Voron V2.4 / Moving Gantry Users:** Remember if a gantry is moving along the panel chamber side, the printed intake screws stick out 5mm and will interfere.  Top panel mounting is the only option in that case. The panel mount will work on any side or top panel on a printer with a moving bed system.
