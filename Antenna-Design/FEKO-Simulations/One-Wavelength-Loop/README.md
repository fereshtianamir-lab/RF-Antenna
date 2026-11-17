# One-Wavelength Circular Loop Antenna (FEKO)

[← Back to FEKO Simulations](../README.md)

![Geometry](loop_geometry.png)
![Simulated results](results.png)

**Application:** A simple resonant loop antenna around 1 GHz, used as an element in loop arrays (quad and Yagi-type) and as a teaching reference for resonant loops.
It radiates broadside to the loop plane, with about 3–4 dBi gain.

## Specifications

| Parameter | Value |
|---|---|
| Structure | Circular wire loop in the x–y plane, modelled with 15 straight segments |
| Overall dimensions | Diameter ≈ 96 mm (circumference ≈ 302 mm ≈ 1 λ at 1 GHz) |
| Excitation | Voltage source at one point on the loop; S-parameters referenced to 50 Ω and 85 Ω |
| Resonance | 1.0 GHz, input impedance ≈ 86 − j6 Ω (S11 = −28 dB for 85 Ω, −11 dB for 50 Ω) |
| Frequency range | 0.8–1.2 GHz (UHF / L band) |
| Peak directivity | 2.9–4.6 dBi (3.9 dBi at resonance), maximum normal to the loop |
| Year of design | 2016 (FEKO Suite 7.0) |
