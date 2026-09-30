## Download Latest Character Sheet

**Rifts&reg; Character Sheet** &mdash; [[Download PDF](https://github.com/megaversetools/charactersheet/releases/latest/download/Rifts-Character-Sheet.pdf)] [[View Release Notes & Known Issues](https://github.com/megaversetools/charactersheet/releases/latest)]

## Megaverse Online Project Background

Several years ago I developed a fillable PDF character sheet for my favorite RPG: Rifts&reg;. When I put the character sheet together in [Microsoft Publisher](https://www.microsoft.com/en-us/microsoft-365/publisher), my goal was to create a comprehensive, multi-page sheet that let you track all your gear, skills, and background on one side, and flip over for combat stats, attacks, and abilities on the other.

I created a print-only version and later added JavaScript to a fillable PDF to handle basic bonus calculations. After using it for campaigns over the years, I added supplementary sheets and adjusted math to handle newer rules updates. By then, however, the original `.pub` file had been lost to time, leaving me stuck with the compiled output.

My lofty goals to go back and recreate it sat on the shelf as my kids grew up—until they eventually started playing Rifts&reg; as well. Seeing the next generation pick up the game reignited the project, leading to a complete architectural overhaul under the **Megaverse Online Project** banner.

## The Road to v1.2: A Modern Rebuild

This repository is currently undergoing a ground-up rebuild to bring the classic 4-page character sheet into a clean, maintainable open-source workflow:

1. **Decoupled Architecture:** Visual layout and document generation are handled in [Scribus](https://www.scribus.net/), while all character math and rules logic are modularized into a dedicated `megaversetools/core` JavaScript submodule.
2. **Rules Modernization:** Fixing long-standing legacy bugs, specifically updating attribute bonus calculations from the original 1990s *Rifts&reg;* ruleset to strict compliance with *Rifts&reg; Ultimate Edition*.
3. **Open Access & Accessibility:** Migrating to open-source fonts and dual-licensing the project (MIT for code, CC BY-NC-SA 4.0 for layout) to ensure the sheet remains free, community-driven, and fully compliant with Palladium Books' fan-use policies.

Once the structural Scribus layout is complete, a Python build pipeline will automate assembling the final interactive PDF. 

### Contact Information

Matrix: [@traek:matrix.org](https://matrix.to/#/@traek:matrix.org), Mastodon: [@traek](https://mastodon.social/@traek), Messenger: [@traekmalan](https://m.me/traekmalan)