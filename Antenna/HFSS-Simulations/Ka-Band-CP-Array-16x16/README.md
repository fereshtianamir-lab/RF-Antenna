# Ka-Band Circularly Polarized Phased Array, 16×16 (HFSS)

[← Back to HFSS Simulations](../README.md)

> **Satellite communications:** designed for Ka-band satcom user terminals.

![16x16 array, HFSS model (175 mm × 175 mm)](array_16x16_hfss_model.jpg)
![Stacked-patch element: RO4003 / foam / RO4003 stack-up](element_stackup_3d.png)
![Simulated gain patterns for different beam-steering angles (peak ≈ 31.5 dB at broadside)](beam_steering_gain_patterns.jpg)

**Application:** A large flat-panel phased array for Ka-band satellite-communication terminals (satcom-on-the-move, LEO/GEO user terminals, receive at about 17.7–21.2 GHz).
Corner-truncated stacked patches give circular polarization, and progressive-phase excitation steers the beam electronically.

## Specifications

| Parameter | Value |
|---|---|
| Element | Probe-fed stacked patch with two truncated corners (driven 4.6 mm, parasitic 4.1 mm), two SMA probe ports |
| Stack-up | Rogers RO4003 0.5 mm (εr 3.55) / foam 0.5 mm / Rogers RO4003 0.5 mm; total ≈ 1.6 mm |
| Unit cell | 11 × 11 mm (≈ 0.68 λ at 18.5 GHz) |
| Array | 16 × 16 = 256 elements, finite-array (unit cell + lattice-pair) model with scan-phase excitation |
| Overall dimensions | ≈ 175 × 175 × 1.6 mm aperture |
| Frequency range | 16–21 GHz, Ka-band satellite downlink (spans upper Ku and lower K in IEEE terms); centre 18.5 GHz |
| Scan setting | Broadside (θ = 0°) plus parametric scan variables; simulated beam steering over a wide angular range, with ≈ 31.5 dB peak gain at broadside |
| Design variants in the project | Single element (two orientations, the second rotated 45°), 16 × 16 array |
| Year of design | 2021 (ANSYS Electronics Desktop 2020 R2) |

## Source file (download to simulate)

| File | Description |
|---|---|
| [`Array_Ka-Band.aedt`](Array_Ka-Band.aedt) | ANSYS Electronics Desktop project (ACIS geometry) |

Open it with ANSYS HFSS / Electronics Desktop. The geometry uses the ACIS kernel, so AEDT 2025 R1 and later cannot open it directly: open and save it once in AEDT 2024 R2 (or earlier) to convert it to Parasolid. Simulation results are not included; re-run the analysis setup to regenerate them.
