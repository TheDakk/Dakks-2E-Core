# Dakk's D&D 2e Core (for the Advanced Roleplaying System)

![Dakk's Ultimate Tokens](https://raw.githubusercontent.com/TheDakk/Dakks-Ultimate-Tokens/main/art/cover.webp)

A setting-agnostic D&D 2nd Edition ruleset content module for Foundry VTT's Advanced
Roleplaying System (ARS): classes, races, proficiencies, spells, creatures, equipment,
treasure and tables, converted from **For Gold & Glory**, the Open Game Content
interpretation of 2e. Every image points at Dakk's Ultimate Tokens.

## What you need

1. Foundry VTT 14 (the ARS version this content is built against requires it).
2. The **Advanced Roleplaying System (ARS)** game system, version 2026.08.25 or later:
   `https://github.com/adndmike/advanced-roleplay-system/releases/latest/download/system.json`
3. The **Dakk's Ultimate Tokens** art module, 3.5.0 or later (the images live there; this
   module points at them). Foundry offers to install it when you install this one:
   `https://github.com/TheDakk/Dakks-Ultimate-Tokens/releases/latest/download/module.json`
4. In the world, set the ARS variant to **2** (2nd Edition). Saving throws, THAC0 and thief
   skills are keyed by it.

## Install

In Foundry, **Add-on Modules → Install Module**, paste
`https://github.com/TheDakk/Dakks-2E-Core/releases/latest/download/module.json`.
Or download the release zip and unpack it into `Data/modules/dakks-2e`; with the GitHub CLI,
in PowerShell, Foundry closed:

```powershell
$zip = "$env:TEMP\dakks-2e.zip"
gh release download -R TheDakk/Dakks-2E-Core -p "dakks-2e-*.zip" -O $zip --clobber
Expand-Archive $zip "$env:LOCALAPPDATA\FoundryVTT\Data\modules\dakks-2e" -Force
```

Enable it in your world; Foundry offers to enable the art module with it. If the module unchecks
itself when you enable it, Foundry has found a dependency below its minimum: check that
ARS is 2026.08.25 or later and the art module 3.5.0 or later, then try again.

## What is inside

| Compendium | Type | Documents |
|---|---|---:|
| Classes | Item | 16 |
| Skills | Item | 13 |
| Races | Item | 6 |
| Weapon Proficiencies | Item | 110 |
| Nonweapon Proficiencies | Item | 60 |
| Wizard Spells | Item | 312 |
| Priest Spells | Item | 172 |
| Equipment | Item | 225 |
| Weapons | Item | 75 |
| Armor | Item | 21 |
| Creatures | Actor | 102 + 27 female/male twins |
| Tables | RollTable | 89 |
| Documentation | JournalEntry | 1 |

Where Dakk's Ultimate Tokens paints a woman beside a creature, "Ogre (female)" sits beside
"Ogre" with the same stats and her own portrait and token, so you place the one you want. Every
creature's starting disposition was reviewed against its nature: harmless animals, townsfolk and
good creatures that would not attack on sight start neutral.

## Licence

The rules content is Open Game Content converted from For Gold & Glory under the Open Game
License v1.0a; the full licence and Section 15 are in LICENSE.md. *For Gold & Glory™ and
FG&G™ are trademarks of Justen Brown. This work is not affiliated with Justen Brown.*
Images belong to Dakk's Ultimate Tokens and its licence. Assembly by TheDakk, 2026.
