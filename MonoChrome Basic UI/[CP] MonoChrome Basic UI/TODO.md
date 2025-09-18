# UI Content Support list
## Vanilla
- Vanilla Text Box
- Vanilla screenshot button
- Vanilla calender
- Vanilla daily quests
- Vanilla letters

## Mods
### Supported Via Content Pipeline
#### Bigger Backpack
- [x] LooseSprites/JunimoNote 
#### Convenient Inventory
- [x] Mods/gaussfire.ConvenientInventory/quickStackIcon
- [x] Mods/gaussfire.ConvenientInventory/favoriteCursor
- [x] Mods/gaussfire.ConvenientInventory/favoriteHighlight_0 (through to 6)
- [x] Mods/gaussfire.ConvenientInventory/favoriteBorder
- [x] Mods/gaussfire.ConvenientInventory/autoOrganizeIcon
#### Font settings 
- [x] Mods/Becks723.FontSettings/font-tab
- [x] Mods/Becks723.FontSettings/refresh
- [x] Mods/Becks723.FontSettings/save
- [x] Mods/Becks723.FontSettings/delete
- [x] Mods/Becks723.FontSettings/font-preview-normal
- [x] Mods/Becks723.FontSettings/font-preview-compare
- [x] Mods/Becks723.FontSettings/section-box
- [x] Mods/Becks723.FontSettings/font-button
- [x] Mods/Becks723.FontSettings/export
- [x] Mods/Becks723.FontSettings/spanner
#### Generic Mod Config Menu
- [x] Mods/GenericModConfigMenu/ConfigButton
- [x] Mods/GenericModConfigMenu/KeyboardButton
#### Happy Home Designer
- [x] Mods/tlitookilakin.HappyHomeDesigner/Catalogue
- [x] Mods/tlitookilakin.HappyHomeDesigner/UI
- [x] Mods/tlitookilakin.HappyHomeDesigner/Mail
- [x] Mods/tlitookilakin.HappyHomeDesigner/Overlay
#### Smart building
- [x] Mods/SmartBuilding/ToolButtons        (assets/Buttons.png)
#### Swim Mod
- [x] FlyingTNT.Swim/OxygenBar
#### Vanilla Plus Professions
- [x] VanillaPlusProfessions/ProfessionIcons
- [x] VanillaPlusProfessions/TalentBG
- [x] VanillaPlusProfessions/TalentSchema
- [x] VanillaPlusProfessions/BundleIcons
- [x] VanillaPlusProfessions/SkillBars

---
### Skips Content Pipeline
#### Deluxe journal
- Skips pipeline
#### Mana Bar
- Skips pipeline
#### Quality Colour Smash
- Skips pipeline
#### SpecialPower Utilities
- Skips pipeline

---
### No Source Found
#### Event lookup
- No Source (ILSpy)
#### Stardew and Chill
- No Source (ILSpy)
#### Mod Update Menu [Forum Link](https://forums.stardewvalley.net/threads/unofficial-mod-updates.2096/page-243#post-148313)
- No Source (ILSpy)

---
### Other Temporary Reasons
#### Unlockable Bundles
- Can't find due to GitLab bulshittery

---
### Uses Vanilla Assets
#### Lookup anything
- Uses vanilla assets

---
#### Info to find correct Target Path

<details>
<summary>Info</summary>
Search for `helper.Events.Content.AssetRequested` in mod files to find if assets are loaded via content pipeline
Search for the bit following the previous to find the asset path
<br>
Or search for `.content.Load<Texture2D>`
<br>
Or `LoadFromModFile<Texture2D>` if combined with `if NameWithoutLocale.IsEquivalentTo`
</details>

