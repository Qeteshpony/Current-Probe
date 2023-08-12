# Current-Probe

[![CI](https://github.com/Qeteshpony/Current-Probe/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Qeteshpony/Current-Probe/actions/workflows/ci.yml)

![3D Render](https://qeteshpony.github.io/Current-Probe/3D/Current-Probe-3D_top.png)

[Hardware Documentation](https://qeteshpony.github.io/Current-Probe)

A simple board to turn any oscilloscope into a current meter by running the load through the 4mm Terminals and connecting your oscilloscope to the BNC terminal. 

The resistor footprint takes a 2512 SMD resistor which usually come with a rating of 1 to 3, sometimes 5 watts which is enough to run several amps through this board. 

The connector footprints are made for the `Altech/Hirschmann PB 4` 4mm test jacks that take a standard 4mm test lead. 

The BNC connector footprint is for the `Amphenol B6252HB` but there's lots of cheap, compatible connectors with the same footprint available

You can also use the M3 screw holes to connect to this board since they are wired in parallel to the connectors closest to each. 