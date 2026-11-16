# Quarter-Wave Monopole over a Ground Plane (HFSS)

[← Back to HFSS Simulations](../README.md)

![HFSS model preview](monopole_hfss_preview.png)
![Geometry](monopole_geometry.png)

**Application:** An omnidirectional vertical antenna for UHF systems around 900 MHz, such as vehicle, base-station and IoT terminals.
It is half the size of a dipole thanks to the ground-plane image, and is widely used as a reference design.

## Specifications

| Parameter | Value |
|---|---|
| Structure | Vertical PEC wire over a circular PEC ground plane |
| Overall dimensions | Monopole height 83.3 mm, wire Ø 4 mm, ground plane Ø 200 mm |
| Excitation | 50 Ω lumped port (coax-style annulus at the base) |
| Simulation domain | Air cylinder Ø 200 mm × 333 mm with radiation boundary |
| Frequency range | 0.3–1.5 GHz sweep; designed for 0.9 GHz (UHF) |
| Simulated outputs | S11, VSWR, input impedance Z11, gain pattern |
| Year of design | 2014 (HFSS 14) |
