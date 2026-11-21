# Lounge 3D Planner

A 3D model of the empty lounge, built from the floorplan and listing photos, with a furniture planner on top.

![The empty lounge in 3D](preview.png)

## Files

- `index.html` is the planner. Open it in a browser; it loads three.js from jsDelivr, so it needs an internet connection.
- `lounge-empty.glb` is the empty room as a standalone 3D model (glTF binary, metres, Y up). It opens in Blender, Windows 3D Viewer, most online glTF viewers, and SketchUp with a glTF importer. The origin is the inside corner where the window wall meets the radiator wall.

## What's modelled

| Part | Size or position (estimated) |
| --- | --- |
| Lounge | 367 cm wide × 412 cm long, 240 cm ceiling |
| Door alcove | 120 cm wide, 25 cm deeper than the rest of the door wall |
| Hall door | 80 cm opening, hinged on the radiator side, opens into the lounge |
| Window | about 143 cm wide, beside the teal feature wall |
| Half-height ledge | 18 cm deep, 103 cm high with a black top, under the window |
| Kitchen opening | about 123 cm wide, 200 cm high |
| Radiator | 85 cm column radiator on the radiator wall, by the door |
| Finishes | oak strip floor, pine door and skirting, coving, recessed downlights |

The floorplan has no dimensions, so the sizes are scaled from the door and shower tray widths on the plan. Allow about ±10 cm. If you have the real measurements, type them into the Room tab and the room resizes around your furniture.

## Using the planner

- **Furniture tab:** tap an item to add it, drag it into place, and use the panel to resize, turn, recolour, duplicate or delete it. Items snap to walls. Anything that overlaps furniture, the radiator, the ledge or the door swing turns red.
- **Room tab:** room size, wall colours, floor and woodwork finishes.
- **Views:** 3D (orbit), Top (a plan cut at 1.2 m with dimensions) and Eye level (walk around at standing height).
- **Save & export:** save or open a layout file, download the room as a .glb (empty or furnished), or save a picture.

Your layout is also kept in the browser as you go.
