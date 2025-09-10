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
- LooseSprites/JunimoNote 
#### Convenient Inventory
- Mods/gaussfire.ConvenientInventory/quickStackIcon
- Mods/gaussfire.ConvenientInventory/favoriteCursor
- Mods/gaussfire.ConvenientInventory/favoriteHighlight_0 (through to 6)
- Mods/gaussfire.ConvenientInventory/favoriteBorder
- Mods/gaussfire.ConvenientInventory/autoOrganizeIcon
#### Font settings 
- Mods/Becks723.FontSettings/font-tab
- Mods/Becks723.FontSettings/refresh
- Mods/Becks723.FontSettings/save
- Mods/Becks723.FontSettings/delete
- Mods/Becks723.FontSettings/font-preview-normal
- Mods/Becks723.FontSettings/font-preview-compare
- Mods/Becks723.FontSettings/section-box
- Mods/Becks723.FontSettings/font-button
- Mods/Becks723.FontSettings/export
- Mods/Becks723.FontSettings/spanner
#### Happy Home Designer
- Mods/tlitookilakin.HappyHomeDesigner/Catalogue
- Mods/tlitookilakin.HappyHomeDesigner/UI
- Mods/tlitookilakin.HappyHomeDesigner/Mail
- Mods/tlitookilakin.HappyHomeDesigner/Overlay
#### Smart building
- Mods/SmartBuilding/ToolButtons        (assets/Buttons.png)
#### Swim Mod
- FlyingTNT.Swim/MappedPants
- FlyingTNT.Swim/OxygenBar
- Theres more, all fishes but theres so many
#### Vanilla Plus Professions
- VanillaPlusProfessions/ProfessionIcons
- VanillaPlusProfessions/TalentBG
- VanillaPlusProfessions/TalentSchema
- VanillaPlusProfessions/BundleIcons
- VanillaPlusProfessions/SkillBars

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
#### Generic Mod Config Menu
- Uses vanilla assets
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

