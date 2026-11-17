# RF / Antenna Portfolio

RF antenna and transmission-line models simulated in ANSYS HFSS, CST Microwave Studio and Altair FEKO, including Ka-band phased arrays for satellite communications.

- [Antenna](Antenna/)
  - [HFSS Simulations](Antenna/HFSS-Simulations/)
    - [Ka-band CP phased array 16×16, satellite communications](Antenna/HFSS-Simulations/Ka-Band-CP-Array-16x16/) – 16–21 GHz (Ka)
    - [Ka-band CP phased array 8×8, satellite communications](Antenna/HFSS-Simulations/Ka-Band-CP-Array-8x8/) – 16–21 GHz (Ka)
    - [SIW-fed end-fire antenna](Antenna/HFSS-Simulations/SIW-Antenna/) – 7–13 GHz (X)
    - [Axial-mode helix (RHCP)](Antenna/HFSS-Simulations/Helix-Antenna/) – 1.15–1.33 GHz (L)
    - [Log-periodic dipole array](Antenna/HFSS-Simulations/Log-Periodic-Dipole-Array/) – 54–216 MHz (VHF)
    - [Half-wave dipole](Antenna/HFSS-Simulations/Half-Wave-Dipole/) – 0.9 GHz (UHF)
    - [Quarter-wave monopole](Antenna/HFSS-Simulations/Quarter-Wave-Monopole/) – 0.9 GHz (UHF)
  - [CST Simulations](Antenna/CST-Simulations/)
    - [Discone](Antenna/CST-Simulations/Discone/) – 1–3 GHz (L/S)
  - [FEKO Simulations](Antenna/FEKO-Simulations/)
    - [E-plane sectoral horn](Antenna/FEKO-Simulations/E-Plane-Sectoral-Horn/) – 9.5–10.5 GHz (X)
    - [H-plane sectoral horn](Antenna/FEKO-Simulations/H-Plane-Sectoral-Horn/) – 9.5–10.5 GHz (X)
    - [Sleeve dipole above ground](Antenna/FEKO-Simulations/Sleeve-Dipole-X-Band/) – 7.6–12 GHz (X)
    - [Conical spiral antenna, L-band](Antenna/FEKO-Simulations/Conical-Spiral-Antenna-L-Band/) – 0.8–1.3 GHz (L)
    - [One-wavelength loop](Antenna/FEKO-Simulations/One-Wavelength-Loop/) – 1.0 GHz (UHF/L)
    - [Broadband planar monopole](Antenna/FEKO-Simulations/Broadband-Monopole-VHF/) – 150–340 MHz (VHF)
- [Transmission Line](Transmission-Line/)
  - [Coaxial line](Transmission-Line/Coaxial-Line/) – 1–5 GHz (L/S/C)
  - [Rectangular waveguide](Transmission-Line/Rectangular-Waveguide/) – 2–10 GHz (S/C/X)

## Download and simulate

Every model folder includes the original simulation project file (HFSS `.hfss`/`.aedt`, CST `.cst` or FEKO `.cfx`). Open the file on GitHub and click **Download raw file**, or use **Code → Download ZIP** to get everything. Each README's *Source file* section says which software version opens it. Results are not included; re-run the analysis to regenerate them.

<p align="center"><img src="Antenna/HFSS-Simulations/SIW-Antenna/siw_hfss_preview.png" width="320" alt="SIW antenna HFSS model"></p>
