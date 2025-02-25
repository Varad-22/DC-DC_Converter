# DC-DC_Converter

## Problem Statement

Traditional DC-DC converters like buck and boost suffer from limitations such as high ripple, limited voltage range, and lower efficiency in certain applications. The Zeta and SEPIC converters provide a solution by allowing step-up and step-down voltage conversion with reduced switching noise and improved stability.

## Zeta Converter

- A Zeta converter is a non-isolated DC-DC converter that provides both buck and boost capabilities while maintaining continuous current at both input and output.

- It consists of two inductors, two capacitors, a diode, and a switching MOSFET.

- Working Principle:

  1. In the ON state, energy is stored in the inductors.

  2. In the OFF state, the energy is transferred to the output capacitor.

  3. This results in a smooth, regulated output voltage with reduced ripple
 
## SEPIC Converter

- A Single-Ended Primary Inductor Converter (SEPIC) allows the output voltage to be either greater or less than the input voltage.

- It consists of two inductors, two capacitors, a diode, and a switching MOSFET.

- Working Principle:

  1. During the ON state, both inductors store energy.

  2. During the OFF state, stored energy is transferred to the output capacitor and load.

  3. This topology ensures a non-inverted output voltage and smooth operation.

