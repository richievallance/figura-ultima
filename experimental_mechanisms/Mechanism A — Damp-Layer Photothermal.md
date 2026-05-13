Mechanism A — Damp-Layer Photothermal (Primary Protocol)

A.1 Conceptual Overview

This mechanism is the core hypothesis of the entire study: that a thin, damp linen layer subjected to a controlled radiant-heat flux (120–160 °C surface range) can develop a superficial, non-pigment yellow-brown image purely through oxidation and mild dehydration of the cellulose fibril skin.
Moisture acts as a thermal buffer—absorbing latent heat and delaying pyrolysis—while permitting oxidation in the straw-tone range, just below the Leidenfrost transition (~193 °C).
The result should be an image colour confined to the outer fibril sheath, without pigment deposition or penetration, reproducing the Shroud’s “image without medium.”

A.2 Physical Basis

Process	Parameter	Function

Moisture Buffering	8–15 % w/w water	Raises char threshold; promotes uniform surface oxidation.
Radiant Heat Flux	0.8–2.0 kW m⁻²	Drives oxidation via photothermal absorption; controlled by distance.
Leidenfrost Constraint	~193 °C	Upper limit—evaporation stabilizes surface below charring temp.
Cellulose Oxidation Kinetics	120–180 °C	Produces yellow chromophores (carbonyl, conjugated aldehydes).
Maillard Coupling (optional)	starch + urea film	Catalyzes colour at lower T; enhances gradient continuity.


Superficiality emerges from a narrow balance: radiant energy must exceed the oxidation threshold yet remain below the evaporation-driven buffer that would cause deeper conduction or fibre collapse.

A.3 Apparatus & Setup

1. Linen A: pre-washed, 100 % flax, 0.25 × 0.25 m swatch, tight weave (~24 threads cm⁻¹).


2. Dampening: spray to achieve 10 ± 2 % moisture by mass. Record initial weight.


3. Mount: fix on non-conductive frame above tile/metal base; ensure planar surface.


4. Heat Source: halogen work lamp (400–500 W) with concave mirror or polished bowl (~15 cm diam.) set 0.5–1.5 m from surface.


5. Temperature Monitoring: IR thermometer (spot size ≤ 5 mm) aimed mid-field.


6. Environment: still air; ambient 20–25 °C; relative humidity 40–60 %.


7. Safety: gloves, goggles, spray bottle, extinguisher; fire-proof bench.



A.4 Experimental Sequence

Step	Action	Target / Note

1	Verify cloth moisture; re-spray if below 8 %.	Uniform dampness, no gloss.
2	Position mirror + lamp; align flux normal to linen.	Dist. = 0.8 m for ~150 °C.
3	Begin exposure; maintain IR reading 130–160 °C.	Duration = 3–15 min.
4	Optional: pass light through stencil (aperture 1–5 mm) for image shaping.	Observe developing tone.
5	Terminate before >180 °C. Remove heat.	Cool 5 min ambient.
6	Record surface temp decay curve.	Plot for Digital Twin validation.
7	Air-dry 1 h; store sealed for 24 h before diagnostics.	Stabilise oxidation.


A.5 Expected Optical & Chemical Outcomes

Property	Observation	Verification

Tone	Straw-brown (ΔE ≈ 5–8 vs background)	Grayscale histograms.
Depth	≤ 40 µm proxy (edge micrograph)	USB microscope > 400×.
Binder residue	None	Tape-lift → transparent.
Fluorescence	Under-fluorescent vs control	UV 365 nm LED.
Bleed	None	Water-drop test.
Negative mapping	Light ↔ dark inversion under aperture	Macro imaging.


A.6 Data Capture Workflow

1. Macro imaging (flat-lit + raking-light).


2. Micro edge section (razor slice; side-on).


3. Tape-lift samples (image & background).


4. Water-drop and UV tests.


5. Grayscale line profile extraction (ImageJ / Python).


6. Record: flux (kW m⁻²), time (min), moisture %, temperature range.


7. Repeat × 3 replicates (A1–A3) for statistics.



A.7 Quantitative Benchmarks

Metric	Target	Instrument

Image depth (µm)	≤ 40 (mean ≤ 20 µm)	USB scope, side micrograph
Colour index (L* drop)	ΔL 5–8 vs background	calibrated photo card
Surface T (°C)	130–160 average	IR thermometer
Exposure time (min)	5–12	stopwatch
Moisture %	8–15	mass loss calc
UV intensity ratio	0.85 ± 0.05 of background	UV photo
Tape-lift residue	< 5 % coverage	optical count


