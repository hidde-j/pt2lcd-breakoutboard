# pt2lcd-breakoutboard
Simple LPM015M135A breakout board 

#### Voltage regulator

The LPM015M135A expects 4.5V on VDDP, so an LT3009 voltage regulator is included in the design that steps 5V down to 4.5V.

#### Missing footprints/symbols

The BM20B-24DS and LT3009 footprints are not included due to copyright reasons. These can be found by searching for the part numbers on Digikey. These are the expected file locations:

```
.
├── BM20B-24DS
│   ├── 2024-12-25_12-01-17.kicad_sym
│   ├── BM20B(0.6)-24DS-0.4V(53).STEP
│   └── footprints.pretty
│       └── BM20B0.6-24DS-0.4V53_HIR.kicad_mod
├── LT3009
│   ├── 2024-12-23_21-50-19.kicad_sym
│   ├── 3009fd.pdf
│   └── footprints.pretty
│       ├── DFN-6_DC_LIT.kicad_mod
│       ├── DFN-6_DC_LIT-L.kicad_mod
│       └── DFN-6_DC_LIT-M.kicad_mod
```

