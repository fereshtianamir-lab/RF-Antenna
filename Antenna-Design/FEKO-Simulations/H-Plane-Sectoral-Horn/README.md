# H-Plane Sectoral Horn, X-Band (FEKO)

[← Back to FEKO Simulations](../README.md)

![Simulated S11 and directivity](s11_directivity.png)
![Radiation pattern](radiation_pattern.png)

**Application:** A medium-gain directional antenna for X-band radar, measurement setups and reflector feeds.
Flaring only in the H-plane gives a narrow beam in that plane and a wide beam in the E-plane.

## Specifications

| Parameter | Value |
|---|---|
| Structure | Rectangular waveguide flared in the H-plane, fed by a coaxial pin (monopole probe) |
| Solver | FEKO MoM with MLFMM, YZ-plane magnetic symmetry, 18,338 metallic triangles |
| Excitation | Voltage source on the feed pin, 50 Ω reference |
| Frequency range | 9.5–10.5 GHz, X band |
| Matching | \|S11\| < −17.8 dB over the whole band (best −22 dB) |
| Directivity | 13.6–14.5 dBi; at 10 GHz HPBW ≈ 20° (H-plane) × 56° (E-plane), front-to-back ≈ 21 dB |
| Year of design | 2017 (FEKO Suite 7.0.2) |
