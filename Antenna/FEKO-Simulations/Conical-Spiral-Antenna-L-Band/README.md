# Conical Spiral Antenna, L-Band (FEKO)

[← Back to FEKO Simulations](../README.md)

![3D geometry from the CADFEKO model](conical_log_spiral_3d.png)
![Simulated results](results.png)

**Application:** A circularly polarized, wideband conical spiral antenna for L-band satellite links, GNSS and telemetry, where orientation-independent reception is needed.
The simulated performance shows right-hand circular polarization (axial ratio ≈ 0.2 dB) with about 9.3 dBi directivity across the band.

## Specifications

| Parameter | Value |
|---|---|
| Structure | Two-arm conical log-spiral antenna |
| Overall dimensions | Base Ø 187 mm, apex Ø 29 mm, height 602 mm, 12.9 turns |
| Mesh | FEKO MoM, 2588 metallic triangles, total metal area 0.18 m² |
| Excitation | 50 Ω edge voltage source; input impedance ≈ 90–100 Ω |
| Frequency range | 0.8–1.3 GHz (upper UHF / L band) |
| Peak directivity | 9.1–9.4 dBi, nearly constant over the band |
| Polarization | Right-hand circular, axial ratio ≈ 1.02 (0.2 dB) at boresight, front-to-back ≈ 38 dB |
| Half-power beamwidth | ≈ 68–72° |
| Year of design | 2016 (FEKO Suite 7.0) |
