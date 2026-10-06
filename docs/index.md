## Download Latest Character Sheet

**Rifts&reg; Character Sheet** &mdash; [[Download PDF](https://github.com/megaversetools/charactersheet/releases/latest/download/Rifts-Character-Sheet.pdf)] [[View Release Notes & Known Issues](https://github.com/megaversetools/charactersheet/releases/latest)]

## Megaverse Online Project Background

Several years ago, I developed a fillable PDF character sheet for my favorite RPG: Rifts&reg;. Built originally in [Microsoft Publisher](https://www.microsoft.com/en-us/microsoft-365/publisher), the initial vision was a comprehensive, double-sided character sheet designed to keep skills, and abilities on one side, with combat stats, attacks, and equipment on the other, depending on the current phase of play.

When version 1.1 rolled around, I attempted to update the math to match *Rifts Ultimate Edition* (RUE) rules—though I clearly missed a few things in the process—and expanded the sheet into a 4-page document by adding supplemental sheets 3 and 4. Because players kept mixing up the different versions, I deliberately scrubbed any trace of version 1.0 to prevent confusion, perhaps a bit too successfully. Following multiple cross-state relocations over a two-year span, the original `.pub` source files were lost, leaving the compiled output locked under an inaccessible legacy Adobe Acrobat Professional editing certificate.

My plans to rebuild it sat on the shelf as my kids grew up—until they eventually started playing Rifts&reg; as well. Seeing the next generation pick up the game reignited the project, leading to a complete architectural overhaul under the **Megaverse Online Project** banner.

## The Road to v1.2: A Modern Rebuild

This repository is currently undergoing a ground-up rebuild to bring the classic 4-page character sheet (pages 3 and 4 are always optional to print) into a clean, maintainable open-source workflow:

1. **Decoupled Architecture:** Visual layout and document generation are handled in [Scribus](https://www.scribus.net/), while all character math and rules logic are modularized into a dedicated `megaversetools/core` JavaScript submodule.
2. **Rules Modernization:** Fixing long-standing legacy bugs, specifically updating attribute bonus calculations from the original 1990s *Rifts&reg;* ruleset to strict compliance with *Rifts&reg; Ultimate Edition*.
3. **Open Access & Accessibility:** Migrating to open-source fonts and dual-licensing the project (MIT for code, CC BY-NC-SA 4.0 for layout) to ensure the sheet remains free, community-driven, and fully compliant with Palladium Books' fan-use policies.

Once the structural Scribus layout is complete, a Python build pipeline will automate assembling the final interactive PDF.

### Contact Information

* Matrix: [@traek:matrix.org](https://matrix.to/#/@traek:matrix.org)
* Mastodon: [@traek](https://mastodon.social/@traek)
* Messenger: [@traekmalan](https://m.me/traekmalan)