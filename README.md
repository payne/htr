# Prompt

help me find a nicely formatted one sheet (both sides are ok) reference
guide for the ham radio technician exam. It should include circle with OHM's
law and the other formula wheel. Also the units and common frequency
ranges and common formulas such as relationship between wavelength and
frequency.

# Response
Synthesized ham radio exam reference materials comprehensively
Here's your two-sided Technician exam reference guide, N3PAY. Here's what's packed
into it:

## Side 1 — Electronics, Formulas & Frequencies:
1. E/P/I/R Formula Wheel — a proper color-coded SVG circle (blue=voltage, red=power,
green=current, orange=resistance) with all 12 formulas arranged inside it, plus the
"cover the unknown" hint
1. SI Metric Prefixes — Giga down to Pico with ham radio examples
1. Electrical Units table — Volt, Amp, Ohm, Watt, Hz, Farad, Henry with instruments
1. Frequency ↔ Wavelength — the key 300/f formula with feet version too, plus worked
examples
1. Antenna Lengths — dipole and quarter-wave verticals in both feet and meters (468,
234, 143, 71.5)
1. Reactance,Impedance & Resonance — XL, XC, Z, resonant frequency, series/parallel
L&C combos
1. Decibels & SWR — the power/voltage dB formulas plus the handy ±3/6/10 dB
reference grid
1. Technician Band Privileges table — all 11 bands, freq ranges, allowed modes, and
power limits
1. Common Frequencies — 146.520, 446.000, APRS, 6m calling, NOAA weather,
marine CH 16
1. Repeater Offsets — 2m, 70cm, 6m, 1.25m, 23cm

## Side 2 — Operations, Rules & Safety:
1. NATO Phonetic Alphabet — full A–Z in two columns
1. 14 Q-Signals — the ones actually tested
1. RST Signal Report — readability, strength, tone scales
1. FCC Part 97 Rules — ID requirements (every 10 min), power limits, prohibited
transmissions, third-party traffic
1. Emission Mode Designators — A1A, J3E, F3E, G7W, etc.
1. License Class comparison — Tech/General/Extra at a glance
1. RF & Electrical Safety — MPE, controlled/uncontrolled environments, grounding,
lightning, high-voltage hazards
1. Propagation Modes — Ground wave, ionospheric layers, Sporadic-E, troposcatter,
aurora, meteor scatter, EME
1. Antenna Types — 7 types with impedance, pattern, and notes

# Prompt 2
make the omh's law and power law graphic have their more common forms


Identified notation discrepancy and standardized voltage variable throughout formulas

I can see the wheel uses E (electromotive force notation) throughout, but most people learn Ohm's Law with V for voltage. I'll update all the formulas to use V consistently — so it reads V=IR, P=VI, R=V/I, etc.


Ran a command, edited a file

Now update the section header comment and card title to drop the "E" reference:

Ran a command, read a file

Done. The wheel now uses V throughout — consistent with how virtually every modern textbook and the FCC pool questions phrase it:

* V quadrant: V = IR, V = P÷I, V = √(P×R)
* P quadrant: P = VI, P = I²R, P = V²÷R
* I quadrant: I = V÷R, I = P÷V, I = √(P÷R)
* R quadrant: R = V÷I, R = V²÷P, R = P÷I²

The ARRL traditionally uses E (for EMF), but the ham exam pool itself writes V=IR, so this matches what you'll actually see on the test.

