**Parametric exhaust fitting by Rock217**

This is a parametric clone of the default voron exhaust fitting for use on panels of thicknesses larger than 4mm. If you wish to use this, instead of printing "4-Voron_Chamber_Connection_and_Exhaust.stl", print one "Voron_Exhaust_fitting" with the desired panel thickness, and one each of the stls in "Voron_Chamber_Connection_and_Exhaust".

If you wish to use a panel thickness not supplied, simply open "Voron_Exhaust_Fitting_Parametric.f3d" and modify the "panel_thickness" parameter.

Use the following information to get your new screw sizes.

Current affected screws
M3x10 x4
M3x12 x7
M3x25 x2

Each screw length is to be increased by panel_thickness-4.

New screws
4x: M3x(6+panel_thickness) (Threads into heat set inserts in the flow chamber, followed by empty air. Probably ok to be long by a few mm)
7x: M3x(8+panel_thickness) (Threads into 11mm holes in the flow chamber, probably ok to be short by a few mm)
2x: M3x(21+panel_thickness) (Important, these hold the filter/panel to frame. Try to get these in the correct length)

Example:
I want a 14mm panel. I will need:

4x: M3x20 SHCS
7x: M3x22 SHCS
2x: M3x35 SHCS

In the default configuration, the M3x12 screws thread directly into an 11mm hole in the voron exhaust fitting. As 22mm is an odd screw size, M3x20 SHCS screws will suffice for these screws. 35mm and 20mm are common screw lengths so no changes are needed.



