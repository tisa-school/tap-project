# Full-face Minecraft Creeper enclosure — fit prototype

Approved layout: **103 mm wide × 46 mm deep × 222 mm high** assembled (10.3 × 4.6 × 22.2 cm). The head has a complete Creeper face; the micro:bit's red 5×5 display faces forward through the body opening. The camera can go on either head side. There are no hearts or separate pedestal. The small fixed side cover provides space for the hub's camera cable connector.

This rehouses the electronics and replaces the original brick tower/base. It does not fit over that whole original assembly. The head front is 82 × 82 mm and intentionally shallow to save counter space. This is the compact layout developed for the assumed electronics; an absolute minimum size cannot be established without their measurements.

## What to print

Print one of each of the six numbered case pieces. Use millimetres and **100% scale** in Tinkercad or Bambu Studio. Do not shrink the whole model: that also shrinks the electronics cavities and screw holes.

| No. | Piece | Supplied print orientation: X × Y × Z (mm) |
|---|---|---|
| 01 | Body front | 103 × 139.5 × 23 |
| 02 | Body back | 103 × 139.5 × 23 |
| 03 | Head front | 82 × 82.5 × 23 |
| 04 | Head back | 82 × 82.5 × 23 |
| 05 | Camera foot pad | 24.4 × 32 × 2.5 |
| 06 | Unused camera-port cover | 53.6 × 41.6 × 1.2 |

The two files beginning `00_optional_` are small test pieces, not extra case parts. The hub-outline test checks the published 59.8 × 82.4 mm footprint only. The fastener test checks an M3 clearance hole/nut recess and the M2 pilot hole with your actual filament and screws. Neither verifies the full electronics fit.

All six supplied pieces fit the Bambu P1S's 256 × 256 × 256 mm build envelope. Start with the test pieces. Use the matching P1S printer profile, put each case section on its own plate, inspect the sliced layers and generate supports where needed. These meshes have not been sliced in Bambu Studio or print-tested; orientation alone does not remove every unsupported region. Remove all supports before installing electronics. No G-code is included.

## Hardware to buy or reuse

- 6 × M3×30 mm flat-head machine screws (four for body, two for head)
- 2 × M3×16 mm machine/pan-head screws (rear neck brackets)
- 8 × standard M3 hex nuts, 5.5 mm across flats
- 2 × M2×4 mm self-tapping screws (unused-port cover)
- 4 cable ties, at most 3.5 mm wide: two approximately 250 mm for the hub and two approximately 150 mm for the camera foot
- Existing compatible camera IIC lead

Hardware sizes are design targets, not physically tested fits. Use the fit-test piece first and do not force a screw or nut into place.

## Assembly and colour

Follow `Assembly-instructions.pdf` or `02-assembly-instructions.png`. Join the two back sections at the neck first while the front sections are off. Fit the upright hub with the micro:bit connected and its display aligned with the front opening. Fit the camera foot to the pad, choose a head side, connect the camera, close the fronts and cover the unused side port. Changing the camera side requires reopening the head. Keep the real controls, connectors and camera field of view clear during the dry fit.

STL contains shape only. The engraved Creeper eyes and mouth need black paint or slicer colour painting. Use green filament or paint and add green pixel patches using `Creeper-pixel-colour-reference.svg`. The coloured illustrations show the intended finish, not colours stored in the STL. Avoid paint on the lens, display, buttons, mating faces and screw channels.

## Dimensions and limits

All six case parts are closed, connected meshes. Digital checks found no solid interference with the illustrative hub, full micro:bit depth envelope, cable-plug zone and either camera position; intentional seating contacts remain. **The case has not been fitted to real electronics, print-tested or strength-tested.** Those digital checks cannot establish actual fit, cable bend clearance, camera field of view or print support requirements.

The components below are likely matches from the photo; exact model revisions are unconfirmed:

- ELECFREAKS Nezha EF05043: 59.8 × 82.4 mm published footprint. **35 mm thickness is assumed**, not supplied by the drawing. [Manufacturer reference](https://github.com/elecfreaks/learn-en/blob/master/microbitExtensionModule/nezha.md)
- ELECFREAKS Smart AI Lens EF05045: 35.96 mm width, 60.90 mm total height including foot, 23.80 mm foot width. **24 mm thickness, optical centre and connector positions are assumed.** [Manufacturer reference](https://github.com/elecfreaks/learn-en/blob/master/microbitplanetX/ai/Plant_X_EF05045.md)
- micro:bit V2: 51.60 × 42.00 mm board with an 11.65 mm overall depth envelope. Display/button positions in illustrations are approximate. [Foundation reference](https://github.com/microbit-foundation/dev-docs/blob/main/hardware/2-0-revision.md#mechanical)

Check these against the real devices and confirm free space beside the tap before large prints. This case is unsealed and is not waterproof.

## Editing

Keep both files in `Source/` together. Open `Creeper-Minecraft.scad` in OpenSCAD; its reference STL is required. Choose the `part` name (`body_front`, `body_back`, `head_front`, `head_back`, `camera_pad`, `port_cover`) and leave `print_orientation=true` to export a printable part. For Tinkercad, import the individual numbered STL files instead. Use the current kit's matching pieces and hardware together; earlier kits have different joints and screws.
