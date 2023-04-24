---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.1.0
BobCat Industries (BOB)
created: 09 Sep 2023
updated: 24 Apr 2023

TEMPLATE: ManualInstallation.md v1.1.9.0
created: 01 Feb 2022
updated: 27 Mar 2023

based upon work by Lisias -->

## [BobCat Industries (BOB)][mod]

[Home](./index.md)

Adds BobCat Industries's agent, flags, and common config files used in all Fuel Tanks Plus add-ons for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `FuelTanksPlus` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/FuelTanksPlus/BobCatInd`
* Extract the package's `FuelTanksPlus` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/FuelTanksPlus` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/FuelTanksPlus/BobCatInd`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/FuelTanksPlus/BobCatInd`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/FuelTanksPlus/BobCatInd`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [BobCat]
      + [BobCatInd]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Resources]
          ...
          ManualInstallation.htm
        * #.#.#.#.htm
        * Attributions.htm
        * BobCatInd.version
        * CC-BY-SA-4.0.txt
        * changelog.md
        * readme.htm
        ...
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

THIS FILE: CC BY-ND 4.0 by zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/BobCatInd "BobCat Industries (BOB)"