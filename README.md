# megaversetools/charactersheet

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Megaverse Character Sheet

Welcome to the Megaverse Character Sheet repository. This project represents a complete architectural overhaul and modern ground-up rebuild of a comprehensive, multi-page interactive character sheet originally crafted in Microsoft Publisher. 

### Current Status & History
The current release (tagged as **[1.1](https://github.com/megaversetools/charactersheet/releases/tag/1.1)**—though a 1.0 existed years ago, an exhaustive campaign to remove it from the timeline appears to have been largely successful) is available directly in this repository with its known legacy bugs intact. While detailed issue tracking for these quirks will be logged in the future, the artifact remains hosted here as a baseline reference.

### The Road to 1.2
With the original source files long lost, this repository establishes a clean, maintainable engineering workflow for the upcoming **1.2** release. Even though this represents a complete architectural rewrite under the hood, the goal is targeted modernization and bug correction rather than a redesign:

* **Decoupled Architecture:** Visual layout and document generation are handled in Scribus, while all character math and rules logic are modularized into the `megaversetools/core` submodule.
* **Rules Modernization:** The core driver of this overhaul is fixing long-standing legacy bugs—specifically updating attribute bonus calculations from the original 1990s *Rifts&reg;* ruleset to strict compliance with *Rifts&reg; Ultimate Edition*.
* **Layout Preservation:** The visual design of the sheet will remain fundamentally unchanged. The only expected modifications are a subtle footer update to include the version number and a GitHub repository reference (space permitting), alongside a move to open-source fonts to ensure the Scribus project files remain fully accessible and editable for anyone.

Once the structural Scribus layout is fully rebuilt, the 1.2 release will drop in with clean, version-controlled code and proper math without disrupting the classic look of the sheet.

---

## Why CC BY-NC-SA 4.0?

This repository uses a Non-Commercial ShareAlike license to ensure the project remains a free, community-driven resource while protecting against unauthorized commercial exploitation or paywalls. This commercial restriction respects the intellectual property boundaries of Palladium Books, keeping fan-made design assets strictly non-commercial. To use a truly "open" license that allows commercial application would violate the long-standing guidelines laid out by Palladium Books, Inc. to create fan-made utilities, such as this.

## Legal & Trademarks

&copy; 2026 Traek W Malan. Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

This project is an independent fan-made utility and is not affiliated with, endorsed, or sponsored by Palladium Books Inc. Rifts&reg;, Beyond the Supernatural&trade;, and all associated trademarks, logos, and game terms are the intellectual property of Palladium Books Inc. and Kevin Siembieda.