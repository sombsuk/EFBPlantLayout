# EFBPlantLayout: Multi-Floor MINLP Layout for Empty Fruit Bunch Biodiesel Production

[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.rico.2025.100624-blue)](https://doi.org/10.1016/j.rico.2025.100624)
[![Journal](https://img.shields.io/badge/Journal-Results%20in%20Control%20%26%20Optimization-orange)](https://www.sciencedirect.com/journal/results-in-control-and-optimization)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Open Access](https://img.shields.io/badge/Open-Access-green)](https://doi.org/10.1016/j.rico.2025.100624)
[![GAMS](https://img.shields.io/badge/Code-GAMS-red)](https://www.gams.com/)

## About

This repository contains the GAMS optimization code, AutoCAD layout drawing, and walkthrough video accompanying the paper on **comprehensive multi-floor plant layout optimization** for **Empty Fruit Bunch (EFB) biodiesel production**. The framework formulates a **Mixed-Integer Nonlinear Programming (MINLP)** model that co-optimizes equipment materials, floor assignments, section placement, and passive protection under quantified safety constraints.

## Associated Publication

> **Sukpancharoen, S., Janta-in, C., Sakdee, P., & Srinophakun, T. R.** (2025). Comprehensive plant layout optimization for empty fruit bunch biodiesel production: A multi-floor MINLP approach with safety integration. *Results in Control and Optimization*, *21*, 100624. https://doi.org/10.1016/j.rico.2025.100624

**Open Access** under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0) license — freely available at [ScienceDirect](https://doi.org/10.1016/j.rico.2025.100624).

## Key Features

- **Comprehensive MINLP formulation** that simultaneously co-optimizes:
  - Equipment material selection
  - Floor assignment
  - Section placement
  - Passive protection elements
- **Quantified safety integration** as part of the optimization, not a post-hoc check.
- **Real-world case study** based on Empty Fruit Bunch (EFB) — a major palm-oil-mill byproduct — as biodiesel feedstock.
- **Three-dimensional layout visualization** via AutoCAD drawing and walkthrough video.

## Repository Structure

```
EFBPlantLayout/
├── GAMS code.txt        # MINLP optimization code (GAMS)
├── Real Three.dwg       # AutoCAD drawing of the optimized 3D plant layout
├── walk through.wmv     # Walkthrough video of the optimized layout
└── README.md            # This file
```

| File | Format | Purpose |
|------|--------|---------|
| `GAMS code.txt` | Plain text | Complete GAMS script implementing the multi-floor MINLP formulation. Rename to `.gms` before running in GAMS. |
| `Real Three.dwg` | AutoCAD drawing | Three-dimensional representation of the optimized multi-floor EFB biodiesel plant layout. |
| `walk through.wmv` | Video | Visual walkthrough of the optimized plant layout, illustrating equipment placement across floors and sections. |

## Software Requirements

| Software | Purpose | Notes |
|----------|---------|-------|
| **GAMS** (≥ 36) | MINLP optimization | Requires a solver capable of MINLP (e.g., DICOPT, BARON, SBB, ANTIGONE). Rename `GAMS code.txt` → `GAMS code.gms` before opening. |
| **AutoCAD** (or compatible viewer) | Open `.dwg` file | Free options: AutoCAD Web, DWG TrueView, LibreCAD, eDrawings Viewer. |
| **Video player** | View `.wmv` walkthrough | Windows Media Player, VLC, or any standard player. |

## Usage

### Download

```bash
git clone https://github.com/sombsuk/EFBPlantLayout.git
cd EFBPlantLayout
```

Or download individual files directly from the GitHub web interface.

### Recommended Workflow

1. Watch `walk through.wmv` to get an overview of the optimized layout solution.
2. Open `Real Three.dwg` in AutoCAD (or any compatible DWG viewer) to inspect the 3D plant layout in detail.
3. Rename `GAMS code.txt` to `GAMS code.gms`, open it in GAMS, and configure the solver options as needed.
4. Solve the MINLP problem to reproduce or extend the optimization results.

For full methodological details — including the mathematical formulation, decision variables, objective functions, safety constraints, and parameter values — please refer to the [associated publication](https://doi.org/10.1016/j.rico.2025.100624).

## Citation

If you use the code or layout files in this repository, please cite:

**BibTeX:**
```bibtex
@article{Sukpancharoen2025efb,
  title   = {Comprehensive plant layout optimization for empty fruit bunch biodiesel production: A multi-floor MINLP approach with safety integration},
  author  = {Sukpancharoen, Somboon and Janta-in, Chayangkul and Sakdee, Pakon and Srinophakun, Thongchai Rohitatisha},
  journal = {Results in Control and Optimization},
  volume  = {21},
  pages   = {100624},
  year    = {2025},
  doi     = {10.1016/j.rico.2025.100624},
  url     = {https://doi.org/10.1016/j.rico.2025.100624}
}
```

## Authors and Affiliations

| Author | Role | Affiliation |
|--------|------|-------------|
| **Somboon Sukpancharoen** | First author | Department of Agricultural Engineering, Faculty of Engineering, Khon Kaen University, Thailand |
| Chayangkul Janta-in | Co-author | (b) — see publication for affiliation details |
| Pakon Sakdee | Co-author | Department of Agricultural Engineering, Faculty of Engineering, Khon Kaen University, Thailand |
| **Thongchai Rohitatisha Srinophakun** | **Corresponding author** | Department of Chemical Engineering, Faculty of Engineering, Kasetsart University, Thailand |

## License

This repository is released under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** license, consistent with the open-access publication. This means you may:

- ✅ **Share** — copy and redistribute the material in any medium or format
- ✅ **Attribute** — give appropriate credit to the authors and cite the publication

But you may **not**:

- ❌ **NonCommercial** — use the material for commercial purposes without permission
- ❌ **NoDerivatives** — distribute modified versions of the material

For full license terms, see [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

## Contact

**For questions about the publication:**
Prof. Thongchai Rohitatisha Srinophakun *(Corresponding Author)*
Department of Chemical Engineering, Faculty of Engineering
Kasetsart University, Bangkok 10900, Thailand

**For questions about this repository:**
Assoc. Prof. Somboon Sukpancharoen, Ph.D. *(Repository Maintainer)*
Department of Agricultural Engineering, Faculty of Engineering
Khon Kaen University, Khon Kaen 40002, Thailand
📧 sombsuk@kku.ac.th
