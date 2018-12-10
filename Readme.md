Part Overhaul Integration
===

The Part Overhauls mod was published by Squad during the KSP 1.2 Prerelease to showcase the new PartUpgrade feature and to preview the planned [Rocket Engine Overhaul](http://i.imgur.com/iINdJyL.jpg). It adds two new engines and refreshes several existing 1.25m parts.

This is a set of configurations to better integrate the overhauled parts into the game by hiding the old (now redundant) stock parts and addressing several related issues.

### Dependencies

Required, not included:
- [PartOverhauls](http://kerbalspaceprogram.com/files/PartOverhauls.zip) by Porkjet/Squad
- [ModuleManager](http://forum.kerbalspaceprogram.com/index.php?/topic/50533-121-module-manager-274-november-14th-better-late-than-never/) by sarbian

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
 - Deprecated stock parts get a -Z suffix
 - Deprecated PartOverhaul parts get a -PO suffix
- A missing thrust upgrade for the Heavy Rocketry node has been implemented

### Feature Wishlist

- Convert variants from separate to switchable parts

### Support

Report any bugs, issues, requests, or suggestions via [GitHub](https://github.com/LouisB3/PartOverhaulIntegration).

### License

Part Overhaul Integration by LouisB3 is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
