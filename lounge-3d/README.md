# Lounge 3D Planner

A 3D model of the empty lounge, built from the listing's measurements, floorplan and photos, with a furniture planner on top.

![The empty lounge in 3D](preview.png)

## Files

- `index.html` is the planner. Open it in a browser; it loads three.js from jsDelivr, so it needs an internet connection.
- `lounge-empty.glb` is the empty room as a standalone 3D model (glTF binary, metres, Y up). It opens in Blender, Windows 3D Viewer, most online glTF viewers, and SketchUp with a glTF importer. The origin is the inside corner where the window wall meets the radiator wall.

## What's modelled

| Part | Size or position | Source |
| --- | --- | --- |
| Lounge | 345 cm wide × 434 cm from the window wall to the hall door | Listing |
| Kitchen | 343 cm × 229 cm | Listing |
| Ceiling | 240 cm | Estimate |
| Door recess | 110 cm wide, 25 cm deeper than the shower-room wall (so 409 cm along the feature wall) | Estimate, fits the 229 cm shower room |
| Hall door | 80 cm opening, hinged on the radiator side, opens into the lounge | Plan and photos |
| Window | about 143 cm wide, beside the teal feature wall | Plan and photos |
| Half-height ledge | 18 cm deep, 103 cm high with a black top, under the window | Photos |
| Kitchen opening | about 123 cm wide, 200 cm high | Plan and photos |
| Radiator | 85 cm column radiator on the radiator wall, by the door | Photos |
| Finishes | oak strip floor, pine door and skirting, coving, recessed downlights | Photos |

The room's overall size comes from the listing. Positions of the door, window, opening and radiator are scaled from the floorplan and photos, so allow about ±10 cm on those. Any size can be changed in the Room tab and the room resizes around your furniture.

## Using the planner

- **Furniture tab:** tap an item to add it, drag it into place, and use the panel to resize, turn, recolour, duplicate or delete it. Items snap to walls. Anything that overlaps furniture, the radiator, the ledge or the door swing turns red.
- **Room tab:** room size, wall colours, floor and woodwork finishes.
- **Views:** 3D (orbit), Top (a plan cut at 1.2 m with dimensions) and Eye level (walk around at standing height).
- **Save & export:** save or open a layout file, download the room as a .glb (empty or furnished), or save a picture.

Your layout is also kept in the browser as you go.
