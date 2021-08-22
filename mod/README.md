# Overview

Are you a fanatic xenophile when it comes to blue aliens? Do you wish Silfae's "Animated Asari Portraits" mod was up-to-date?  This mod is for you! With this mod, now you can play the Asari Republics as designed and use all the gameplay elements for your own empires.

There are lots of other mods which contain these portraits, so why should you choose this one? Silfae's art style meshes well with Stellaris, or maybe you want to play her version of the Asari Colonies - content which this mod again makes playable.  Please enjoy my translation of Silfae's custom empire into modern Stellaris.

# Changes

All gameplay features from the original mod are upgraded to be fully compatible with Stellaris 3.0.*, the latest version when this was written.  Updates include:

* Code now sets any leader using the Asari portrait to have `gender = female`
    * All your Asari-portrait leaders will show as Female in the UI and use female pronouns (she/her/hers)
    * Events (hidden) fire on game start, leaders spawning, when elections begin
* Improve Asari portrait definitions and selectors
    * Clothing selectors influenced by Pop job
    * Fix syntax error in Asari mesh definitions
    * Reduce duplication in portrait entity definitions, mesh definitions, and asset selectors
* Update the namelist to account for all built-in army types, remove obsolete entries; Army names more lore-friendly
* Add custom trait "Asari Longevity" to the Asari species class
    * This trait makes their leaders begin at an older age
    * Add bonus lifespan to compensate for their older starting age
    * Automatically given to any species designed with the Asari portraits for free
    * Enhanced art from original trait
* Replace original Asari trait with "Cellular Regeneration" that grants the majority of the age boost (and leader XP penalty) and is available for any species to use
* Update prescripted empire for 3.0
    * Now has Origin: Prosperous Unification
    * Some negatives of the original Asari trait had corresponding negative traits, so Deviants and Slow Learners were added instead
    * Added Unruly - Asari government is extremely decentralized and "young" Asari tend to be restless and rebellious, it seemed to fit
    * Can randomly spawn
    * Gains Psionic Theory for free

## Compatibility

Compatible with any mod that does not add the same portraits, species class, or art assets.

The Launcher will tell you that some mods are outdated - that is because the dependency is out of date with the game's version number.  This mod overwrites and replaces all incompatible code so that the portrait mod will function as originally designed.  You can safely ignore the out-of-date warning for the dependency mod.

Not compatible with achievements.

### Dependencies

In order for this mod to function, you **must** install the following mod and load it before this one:

[Animated Asari Portraits](https://steamcommunity.com/sharedfiles/filedetails/?id=707779361) by Silfae

### When to Install

This mod should be added before the game has started.  If you remove it from a game in progress, your game may have graphical problems if any species was using the custom portraits.

## Known Issues

Silfae's original mod does not include graphics for ecumenopoleis, so they will fall back to the Avian graphical culture. If anyone knows of a mod that provides said stage-6 city picture, I would be happy to investigate getting permission to reuse the graphics, or add it as a dependency to this one.

## Changelog

* 1.0.0 Initial version

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/asari_portraits_revisited)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.

# Special Thanks

I was inspired to extend the original mod when I saw [Endugu](https://steamcommunity.com/profiles/76561198037630876/myworkshopfiles/)'s [expansion](https://steamcommunity.com/sharedfiles/filedetails/?id=1584824947) of [Silfae](https://steamcommunity.com/profiles/76561198021525667/myworkshopfiles/)'s [Animated Xirmian Portraits](https://steamcommunity.com/workshop/filedetails/?id=881118424).  Modular mods that require downloading the original mod(s) help give credit where credit is due.

An extra special thanks to Silfae for creating and sharing so many detailed, animated portraits for the community.