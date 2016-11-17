Part Overhaul Integration
===

The Part Overhauls mod was published by Squad during the KSP 1.2 Prerelease to showcase the new PartUpgrade feature and to preview the planned [Rocket Engine Overhaul] (http://i.imgur.com/iINdJyL.jpg). It adds two new engines and refreshes the visual appearance of several existing 1.25m parts.

This is a set of configurations to better integrate the overhauled parts into the game by hiding the old (now redundant) stock parts and addressing several related issues.

### Dependencies

Required, not included:
- [PartOverhauls] (http://kerbalspaceprogram.com/files/PartOverhauls.zip) by Porkjet/Squad
- [ModuleManager] (http://forum.kerbalspaceprogram.com/index.php?/topic/50533-121-module-manager-274-november-14th-better-late-than-never/) by sarbian

### Installation

Delete any existing installed version of this mod, then drop the PartOverhaulIntegration folder into your GameData folder wherever KSP is installed.

### Features

- Old versions of overhauled parts are hidden
  - They are removed from the tech tree. In existing saves, this does not affect nodes already purchased
  - They are removed from all categories in the VAB and SPH
  - They are retained in the game files so active craft will still function normally
- Testing contracts are added to overhauled parts (copied from old part versions)
- Part variants are renamed to distinguish between them
 - Attachment ring engine variants get a -A suffix
 - Boattail engine variants get a -B suffix
 - Compact engine variants (not published) would get a -C suffix
 - Old part variants get a -Z suffix
- FilterExtensions support (overhauled parts are added to the Squad category)

### Known Issues

- The Mk1 Command Pod has a curved surface protruding over the bottom node, creating visual clipping issues with heat shields (or other parts) attached below

### Feature Wishlist

- Flatten the bottom of the Mk1 Command Pod to fix visual clipping issues
- Use B9PartSwitch or similar to convert variants from separate to switchable parts

### Support

Report any bugs, issues, requests, or suggestions via [GitHub] (https://github.com/LouisB3/PartOverhaulIntegration).

### License

Part Overhaul Integration by LouisB3 is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License] (http://creativecommons.org/licenses/by-nc-sa/4.0/).
