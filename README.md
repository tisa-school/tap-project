# Creeper front-display print kit

**Latest: [download the eight-part print kit and illustrated instructions](Creeper-front-display-kit.zip).**

The red micro:bit LED display faces forward. The camera holder fits either side of the head, with a removable cover over the unused port. There are no hearts.

- [Illustrated assembly booklet (PDF)](Creeper-assembly-guide.pdf)
- [Numbered print-parts picture](Creeper-parts.png)
- [Six-step assembly picture](Creeper-assembly-steps.png)
- [Individual STL files](Creeper-kit/STL)

## Eight printed pieces

| No. | Piece | Download |
|---|---|---|
| 01 | Body front | [STL](Creeper-kit/STL/01_body_front.stl) |
| 02 | Body back | [STL](Creeper-kit/STL/02_body_back.stl) |
| 03 | Head front | [STL](Creeper-kit/STL/03_head_front.stl) |
| 04 | Head back | [STL](Creeper-kit/STL/04_head_back.stl) |
| 05 | Bottom tray | [STL](Creeper-kit/STL/05_bottom.stl) |
| 06 | Unused-port cover | [STL](Creeper-kit/STL/06_camera_cover.stl) |
| 07 | Hub holder | [STL](Creeper-kit/STL/07_hub_cradle.stl) |
| 08 | Camera holder | [STL](Creeper-kit/STL/08_camera_cradle.stl) |

Print one of each in millimetres at 100% scale. Orientations are supplied; all pieces fit the Bambu P1S build volume. Inspect support generation in Bambu Studio before printing. Start with the optional hub-outline test and small holders to check the real hardware.

## Additional hardware

16 × M3×20 screws, 2 × M3×12 screws, 18 standard M3 nuts, two 10 mm hook-and-loop straps and two small cable ties. The illustrated booklet gives the locations and sequence. Hardware dimensions and quantities are for the prototype design, not a physically validated build.

## Prototype limits

The parts are closed, connected meshes and their reference envelopes were checked for geometric interference. **They have not been print-tested, sliced in Bambu Studio, load-tested or fitted to the real electronics.** Hub thickness, camera thickness, connector locations, lens position/field of view and mounting tolerances still need physical validation. The design rehouses the electronics rather than enclosing the original custom brick tower/base.

The illustrations use an assumed 35 mm hub thickness and 24 mm camera thickness. Confirm actual hardware before large prints; do not force a fit. Source files and the detailed limitations are included in the ZIP.

## Manufacturer references

- [ELECFREAKS Smart AI Lens EF05045](https://github.com/elecfreaks/learn-en/blob/master/microbitplanetX/ai/Plant_X_EF05045.md): 35.96 mm wide × 60.90 mm total height with foot.
- [ELECFREAKS Nezha EF05043](https://github.com/elecfreaks/learn-en/blob/master/microbitExtensionModule/nezha.md): 59.8 × 82.4 mm footprint.
- [micro:bit Foundation mechanical specification](https://github.com/microbit-foundation/dev-docs/blob/main/hardware/2-0-revision.md#mechanical): 51.60 × 42.00 mm board.

These are likely matches from the photo; revision labels are not confirmed. The cited drawings do not supply the missing camera/hub thicknesses.

## Older files

`Creeper.stl` is the old 290 mm one-piece figurine and exceeds the P1S build height. `Creeper-case-revision.zip` is an earlier top-display prototype. Use the latest front-display kit linked above for the requested layout.
