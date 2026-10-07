# megaversetools/charactersheet

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview & Architecture

This repository contains the source assets, Scribus layouts, and build scripts for the open-source **Rifts&reg; Character Sheet** (v2.0). Following the loss of the original Microsoft Publisher source files across multiple cross-state relocations, this project establishes a clean, decoupled engineering workflow for the classic 2-page, double-sided character sheet:

* **Layout Generation (`.sla`):** Visual design assets are managed natively in [Scribus](https://www.scribus.net/) utilizing open-source fonts to ensure full project editability.
* **Rules Engine (`megaversetools/core`):** Character math, interactive PDF form calculations, and rules logic are modularized into a dedicated Git submodule adhering strictly to *Rifts&reg; Ultimate Edition* (RUE) standards.
* **Build Pipeline:** A Python-based automation script compiles the Scribus output and injects the core JavaScript logic to generate the final interactive PDF.

## Repository Structure

```text
├── core/                # Submodule pointing to megaversetools/core (JavaScript rules & math)
├── docs/                # GitHub Pages site source (project background and web documentation)
├── fonts/               # Open-source typography assets
├── scribus/             # Scribus project layout files (.sla) and vector graphics (SVG)
└── scripts/             # Python build and PDF assembly pipeline
```

---

[![Active Development](https://img.shields.io/badge/branch-v2--rebuild-blue?style=flat-square&logo=git)](https://github.com/megaversetools/charactersheet/tree/v2-rebuild)

## Why CC BY-NC-SA 4.0?

This repository uses a Non-Commercial ShareAlike license to ensure the project remains a free, community-driven resource while protecting against unauthorized commercial exploitation or paywalls. This commercial restriction respects the intellectual property boundaries of Palladium Books, keeping fan-made design assets strictly non-commercial. To use a truly "open" license that allows commercial application would violate the long-standing guidelines laid out by Palladium Books, Inc. to create fan-made utilities, such as this.

## Legal & Trademarks

&copy; 2026 Traek W Malan. Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

This project is an independent fan-made utility and is not affiliated with, endorsed, or sponsored by Palladium Books Inc. Rifts&reg;, Beyond the Supernatural&trade;, and all associated trademarks, logos, and game terms are the intellectual property of Palladium Books Inc. and Kevin Siembieda.