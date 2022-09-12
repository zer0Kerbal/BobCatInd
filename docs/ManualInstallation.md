---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
BobCat Industries (BOB)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# BobCat Industries (BOB)

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
    + [FuelTanksPlus]
      + [Assets]
        ...
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
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * changelog.md
        * CC-BY-SA-4.0.txt
        * BobCatInd.version
          ManualInstallation.htm
        * readme.htm
        ...
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none
