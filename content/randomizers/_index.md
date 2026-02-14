---
title: Randomizers
resources:
    - name: "mfor.png"
      src: "mfor.png"
      title: "MFOR Options"
    - name: "apworld.png"
      src: "apworld.png"
      title: "APWorld Options"
    - name: "randovania.png"
      src: "randovania.png"
      title: "Randovania's Preset Screen"
---

Randomizers are pieces of software that modify/randomize specific aspects in the original game in order create a new experience each time you play. Several randomizers for Metroid Fusion exist.

## MFOR

Short for Metroid Fusion Open Randomizer (open, as in open game world), it was originally released on 2021-06-20 and is developed by Kazuto. The download can be found on [Metroid Construction](https://metroidconstruction.com/resource.php?id=714).  

{{< columns >}}

Most notable features:
- All major abilities are shown as a ?-Tank. 
- Option to addittionally also hide tanks as well
- Elevator shuffle 
- Tube shuffle
- Palette shuffle
- Major/Minor split 
- Option to unlock all lesser security keycards when collecting higher ones
- Option to be able to fire Missiles after collecting any Missile ability
- Option to be able to only use Power Bombs after having collected Bombs

<--->

{{< img name="mfor.png" size="small" >}}

{{< /columns >}}


The exact license of it is unproven. Earlier versions used to come with a GPLv3 license, but no source code was ever given out. Newer versions come with no license and have been seemingly relicensed as All Rights Reserved.

## OpenMFOR

A decompilation effort of MFOR, that got created due to MFOR's source code never being provided. OpenMFOR was originally released on 2024-08-29 and developed by LucentW and magical. Downloads can be found [on its release page](https://git.inabaudonge.reisen/OpenMFOR/OpenMFOR/releases).

The featureset is exactly the same as MFOR. Efforts have been done to make the code also run on operating systems other than Windows, however one needs to run the program from source for that.

## MARS

Short for Metroid Advanced Randomization System, it was originally released on 2025-02-22 and is developed by the MARS-Team. It's split into a [ASM project](https://github.com/MetroidAdvRandomizerSystem/mars-fusion-asm) that produces a base ROM, and a [python wrapper](https://github.com/MetroidAdvRandomizerSystem/mars-patcher-py) that allows interacting and editing of it. The full list of contributors can be found [here](https://github.com/MetroidAdvRandomizerSystem/mars-fusion-asm/graphs/contributors) and [here](https://github.com/MetroidAdvRandomizerSystem/mars-patcher-py/graphs/contributors) respectively, but notable developers include AntyMew, biospark, cluekitty and Zarakava.

Thus it isn't a randomizer by itself, but rather just provides a base system to implement a randomizer on. It is licensed under the GPLv3, with some graphics being licensed under CC-BY-SA-4.0.  

A few randomizers using MARS exist. While they all have different features, they share the following things in common:
- Prominent event places in the vanilla game are now checks (such as Security rooms or Habitation Deck)
- Security unlocks have been made into items
- All items have unique sprites
- Navigation Rooms give hints
- You can warp to start at any point in order to prevent getting softlocked
- The goal is to collect a predetermined amount of Infant Metroids, Charge Beam and Missiles in order to fight the SA-X


### Randovania

A randomizer platform for a multitude of games. The Fusion integration originally released on 2025-08-01 and is developed by the MARS-Team as well as the Randovania staff. The download can be found [on the Randovania website](https://randovania.org/download/).

{{< columns >}}

Randovania's goal is to deliver a good solo experience.  
Other prominent features include:
- A fully customizable item pool, such as:
  - Being able to start with random or specific items
  - Being able to remove items from the pool completely
  - Shuffling multiple copies of an item
  - Changing how much ammo/health is given by collectibles
- Being able to hide item sprites
- Major/Minor split
- Being able to start in any Save Room of the game
- Customizable trick levels for every trick in the game
- Being able to randomize the door locks/hatches
- Palette shuffle

<--->

{{< img name="randovania.png" >}}

{{< /columns >}}

### APWorld

An external plugin for [Archipelago](https://archipelago.gg/), a cross-game Multiworld randomizer. It was originally released on 2025-06-18 and is developed by Rosalie. The download and setup instructions can be [found on its dedicated wiki page](https://github.com/Rosalie-A/Archipelago/wiki/Metroid-Fusion-Setup-Guide). Note, that it is also included by default in [Multiworld.gg](https://multiworld.gg/).

{{< columns >}}

As was mentioned above, while it can be used as a solo randomizer, the main use is using it in a Multiworld with the many other games Archipelago supports.  
Other prominent features include:  
- Tube shuffle
- Elevator shuffle
- Palette shuffle
- 4 unique starting locations
- Being able to set how much ammo Missiles and Power Bombs give upon collection
- Customizable difficulties for Wall Jumping, Shinesparking and Combat

<--->

{{< img name="apworld.png" >}}

{{< /columns >}}