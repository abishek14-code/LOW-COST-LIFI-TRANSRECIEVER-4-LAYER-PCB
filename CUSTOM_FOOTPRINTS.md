# Project footprints

LiFi_Optics.PcbLib contains project-created native editable footprints. Its unused CAP 0603 template is from Celestial (see Celestial/ATTRIBUTION.md).

- KINGBRIGHT WP7113SRD: 2.54 mm lead spacing; pad 1 cathode, pad 2 anode; 0.9 mm finished holes, 1.8 mm lands. [Manufacturer drawing](https://www.kingbrightusa.com/images/catalog/SPEC/WP7113SRD-D.pdf).
- VISHAY BPW34: 5.08 mm lead spacing; pad 1 cathode, pad 2 anode; 0.9 mm holes, 1.8 mm lands. [Manufacturer drawing](https://www.vishay.com/docs/81521/bpw34.pdf).
- BOURNS MF-NSMF025X: 1.0 x 2.0 mm lands with a 1.6 mm inner gap. [Recommended layout](https://www.bourns.com/docs/product-datasheets/mfnsmf.pdf), page 8.
- TEST PAD 1MM: exposed square 1 mm copper test pad, no purchased component.

These are project footprints, not claimed as Manufacturer Part Search downloads. Final native DRC and assembly review remain required. The crystal is now ABLS-8.000MHZ-B2-T (18 pF load), with 30 pF starting load capacitors assuming 3 pF stray capacitance; tune on the assembled board.
