# JFET-Characteristic-Curve-Analysis
This project analyzed the current–voltage (I–V) characteristics of a JFET transistor. The focus was on extracting key device parameters and understanding how gate–source voltage (VGS) controls drain current (ID).

## Project Overview
This project analyzed the current–voltage (I–V) characteristics of a JFET transistor. The focus was on extracting key device parameters and understanding how gate–source voltage (VGS) controls drain current (ID).

## Methodology
- Constructed test circuits to measure ID vs. VDS at multiple VGS values (0 V, −0.5 V, −1.0 V, −1.5 V).
- Identified linear (ohmic) and saturation regions of operation.
- Compared measured values with datasheet specifications.

## Oscilloscope Usage
The oscilloscope was critical in this project:
- Monitored drain-source voltage stability during sweeps.
- Tracked current-voltage response via sense resistor voltage drop.
- Ensured accurate measurement of transitions between ohmic and saturation regions.

## Outcomes
- Extracted IDSS ≈ 3.46 mA and VGS(off) ≈ −1.5 V.
- Device behavior matched datasheet curves for BF256A/BF245A.
- Validated JFET’s suitability for low-noise analog applications.

