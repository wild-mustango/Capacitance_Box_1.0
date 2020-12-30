# Capacitance_Box_v1

![Capacitance_Box_v1.0](../Capacitance_Box_v1/PCB/TOP.JPG)

## Brief project Description

A circuit that simulates a variable capacitor using knobs to select capacitor values.

I made this project as a "weekend project" inspired by Decade Capacitance Boxes but with the idea of being cheap.
I was made using EasyEDA and sourcing components in LCSC (*not affiliated in any way*). The most expensive parts
are the capacitors.

## Circuit

Why using those particular 8 position switches? Easy, they where the cheapest available in LCSC on that particular moment. My
first idea was to have a 10 position rotary switch with an integrated big knob, but hey!, those are quite expensive (didn't know until
I started selecting components).

In this first revision, association of capacitors in series and in parallel achieve some sort of "decades".

Bear in mid that, although being Samsung and Yageo caps with good dielectrics and tolerances, having associations in series and parallel may affect final tolerance of resulting capacitance.

## PCB

Another objective was to have a small PCB but with big SMD components, at least 0805 and bigger to facilitate soldering.

Using JLCPCB is also very cheap, having 5 PCB under 2 bucks (*not affiliated with JLCPCB neither*).

## Assembly

Since EasyEDA does not provide any kind of Assembly Drawing export, I used the silkscreen for the corresponding assembly drawings.

## Mech Box

I dessigned a box to be easily printable with a 3D Printer in SolidWorks. There you have the STL files and PCBA step model for your convenience.

![Capacitance_Box_v1.0](../Capacitance_Box_v1/Mech/BOX_ASSEMBLY.JPG)

I printed the case using a wall thickness of 0.8mm, 3mm top/bottom solid walls, infill of 30% and a layer thickness of 0.3mm in PLA with good results.
For the knobs I used the same settings as for the case but with a 0.2mm layer thickness.

**I hope you enjoy it making it as I did designing and also making it.**
