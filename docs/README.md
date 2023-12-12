# Assembly Instructions

## Printing the Parts
> [!WARNING]
> Failure to print the tests and callibrate the printer can lead to issues during assembly.

Before printing all the parts, print the test parts in the `../stl/test-prints` folder.
It's extremly important to ensure the printed parts fit together properly.
If they do not, the extrusion multiplier is probably what needs to be modified.

For reference, HM3K was built and tested with the following:
1. Print settings: Voron settings found in the [Voron Sourcing Guide](https://docs.vorondesign.com/sourcing.html) for all parts. The `feeder-block-9.stl` was printed with the infill dropped to 18%
1. Print profiles: Based on [AndrewEllis93's Profiles](https://github.com/AndrewEllis93/Ellis-SuperSlicer-Profiles)
1. Printer Tuning: [AndrewEllis93's Tuning Guide](https://ellis3dp.com/Print-Tuning-Guide/)

The two parts in the Voron Thread Test should screw together easily, not much force.
Once screwed together, there shouldn't be any wobble.

The HM3K test is a simple part which has holes for most of the critical joints used during assembly.
It has:
1. A tight hole in the side for a 6x3 mm magnet
1. A loose hole in the side for a 6x3 mm magnet
1. A hole down the center for testing the PTFE collet, clip, tube and filament
1. A hole to test a 5mm nut, should be snug but not difficult to instert the nut

## Next Step
1. Push extrusions through motor mounts, both directions

The HM3K is divided into two main assemblies, the Feeder (bottom) and the Selector (top).
They are joined with the two spine parts.

Next Step: [Feeder Assembly](./feeder-assembly.md)
