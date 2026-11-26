# OpenPrometheus

> *"From the gods he stole the far-seen gleam of unwearying fire in a hollow stalk—unlocking for humanity the treasures hidden beneath the earth: bronze, iron, silver, and gold."*  
> — Adapted from Hesiod (*Theogony*) & Aeschylus (*Prometheus Bound*)

**OpenPrometheus** is an experimental project aiming to make Laser Powder Bed Fusion (LPBF) more accessible through affordable, modular, and openly documented hardware.

The project explores the development of a compact metal 3D printer using readily available components, conventional manufacturing methods, and 3D-printed parts wherever practical.

The long-term goal is to create an affordable and reproducible platform for experimentation, research, and further development of metal additive manufacturing.

## Target Specifications

The following specifications represent preliminary design goals and may change throughout development.

| Parameter | Target |
|---|---|
| Manufacturing process | Laser Powder Bed Fusion (LPBF) |
| Laser source | Fiber-coupled diode laser, several hundred watts |
| Laser wavelength | Near-infrared (~900–1,000 nm) |
| Build area | Approximately 150 mm diameter |
| Build height | Approximately 30–100 mm |
| Layer thickness | Approximately 80–150 µm |
| Target materials | Iron, stainless steel, and potentially aluminum alloys |
| Motion system | Cartesian XY laser positioning with independent powder recoating |
| Machine construction | Aluminum extrusions, 3D-printed components, and selected metal parts |
| Control system | Open-source motion-control software |

These are development targets rather than validated machine capabilities. Material compatibility, achievable part density, dimensional accuracy, and process reliability remain to be investigated.

## Project Status

OpenPrometheus is currently in the early design and development stage. Its architecture, specifications, and capabilities are subject to change.

The project is experimental and has not been validated for operational use. LPBF involves significant laser, thermal, and metal-powder hazards and requires appropriate engineering controls and safety systems.

## Safety

OpenPrometheus is an experimental project involving
potentially hazardous laser and metal-powder technologies.

The machine has not been validated for safe operation.

See [SAFETY.md](./SAFETY.md) for important safety
information and limitations.

## License

**OpenPrometheus** uses a dual-licensing model to keep both the physical designs and the codebase open to the community:

* **Hardware, CAD & Documentation:** Licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).  
  You are free to share, build, and adapt the hardware for **non-commercial purposes**, provided you give appropriate credit and distribute your modifications under the same license.
* **Firmware, Software & Scripts:** Licensed under the [GNU General Public License v3.0 (GPLv3)](https://www.gnu.org/licenses/gpl-3.0.html).  
  Any derivative software or firmware modifications must also remain open-source under GPLv3.

See the [LICENSE-HARDWARE](./LICENSE-HARDWARE) and [LICENSE-SOFTWARE](./LICENSE-SOFTWARE) files in this repository for full terms.
