# Tactics-Remix

[![Latest Release](https://img.shields.io/github/v/release/gibberlings3/Tactics-Remix?include_prereleases)](https://github.com/Gibberlings3/Tactics-Remix/releases/latest)
[![Github downloads (all releases)](https://img.shields.io/github/downloads/gibberlings3/Tactics-Remix/total.svg?color=informational)](https://github.com/gibberlings3/Tactics-Remix/releases)
![Language](https://img.shields.io/static/v1?label=language&message=english%20%7C%20chinese%20%7C%20spanish&color=informational)
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20macos%20%7C%20linux&color=informational)

[A Gibberlings Three Mod](https://www.gibberlings3.net/)

**Author**: [morpheus562](https://www.gibberlings3.net/profile/11591-morpheus562/)

**On the Web**: [Home Page](https://www.gibberlings3.net/mods/quests/tactics-remix/) and [Discussion Topic](https://www.gibberlings3.net/forums/topic/35950-tactics-remix/)

## Introduction

It is with great pleasure I have been given permission from Wes to update his original [Tactics mod](https://weidu.org/tactics.html) to be compatible with the Enhanced Editions. Tactics Remix adds quite a few optional, but difficult, encounters to BG2:EE and EET aims to make the game more challenging and rewarding.

Many of these components have been drawn from different mod authors; I did not write everything here. In particular, Wes Weimer, Gebhard Blucher, Kensai Ryu, Xyx and Ishan have made contributions. I have gone through, updated the components for the EE's, and redid most of the AI from the ground up. The goal is for the encounters to feel similar to their oBG counterparts with more challenging enemy AI.

## Compatibility

If you are upgrading from an earlier version of this mod, I recommend uninstalling all mod components and replacing all files with the new ones before doing a fresh install. If you choose to use SCS, parts of this mod should be installed before it while other parts should be installed after. These will be clearly outlined during the install process.

These scripts are currently written for a vanilla/SCS understanding of the spells/abilities. Tactics Remix does not take into account other mods that alter existing spells. Some mods do lighter edits that shouldn't impact the scripts, but others, such as Spell Revisions, do a complete overhaul and will cause issues, inconsistencies, and undesired results. As such, I would not recommend install of Tactics Remix if you are playing with Spell Revisions. This may change in the future, but for now I would list these as incompatible.

## Content

Tactics Remix adds quite a few new components, and all of the components are individually optional: you may install some but not others, your choice. I have also broken up the mods into two groups: 1) Add New Encounters and 2) Update Existing Encounters. New encounters should be installed prior to SCS while updates to existing encounters should be installed after SCS (if you, the player, chooses to use SCS).

All of the enemy scripts have been rewritten from scratch and many of the fight mechanics are improved from the old Tactics days. These fights are aimed at being more challenging than the original encounters while removing much of the cheese that players of old remember. These are meant to be BRUTAL. The difficulty slider will alter the overall challenge (e.g. removing undroppable items from enemies to make them easier, less or different enemy spawns, altered enemy prebuffs, etc.). I aim to have a bit of randomness added to the encounters and the scripts are not optimized to always cast the "best" spell. Prebuffs and contingencies/sequencers will vary. Additionally, casters will randomly choose if they will be casting an offensive or a defensive/disabling spell. From there, the enemy scripts will cycle through available spells in the specific category with yet more randomness. Best spells will pop up first, but it is random if the script will choose to cast or pass. This should add a bit of variance to the encounters from reload to reload and hopefully the player enjoys the spontaneity. 

### Add New Encounters - Install BEFORE SCS

#### "Kuroisan", the Acid Kensai

Kuroisan, a Kensai / Wu Jen from Kara-Tur will approach you if you are carrying Celestial Fury or Malakar, regardless if equipped or not. Once you acquire either of these weapons, he will begin the hunt to find you (1 day) and attempt to take yours. Depending on the difficulty level, he may bring additional sword allies to join the fight. 

#### The Ritual

The Ritual component adds a new tactical quest started by speaking with the yellow-robed individual outside of Watcher's Keep. This quest takes the player through some outdoor combat and obscure symbolism against a very pretty backdrop. 

PLEASE NOTE: Original recommendation for party level is around 2 million XP. 

#### "Red Badge" Poison-Based Encounter

This challenge is triggered if you have more than 3 million XP, have either killed Gromnir or be in SoA, and are standing outside of Watcher's Keep. The "Red Badge" will wisk you away with promises to come. Once you have over 3.5 million XP with the same conditions as above, they will bring you back for your confrontation.

#### Gebhard Blucher's Lich in the Docks

A new lich can be found in the Docks district with an endless supply of undead minions to call upon. You may find her by entering the door to the north of the main Shadow Thief guildhouse entrance. 

WARNING: Reported to be *incompatible* with Back to Brynnlaw. 

#### Kensai Ryu's Gnome Fighter/Illusionist in the Docks

A gnome fighter/illusionist full of tricks is looking to collect upon the bounty on Valygar's head. Beware on your search as the gnome will kill anyone in his way. 

### Update Existing Encounters - Install AFTER SCS

These components will check if SCS is present and update accordingly to prevent any compatibility issues.

#### Improved Sahuagin City

This component makes all Sahuagin fiercer opponents. It also updates the fight against the Priestess at the heart of the City of Caverns who will now summon allies to come to her aid. Beware, on Insane Difficulty she will summon the Minor Avatar of Sekolah.

#### Morpheus562's Improved Planar Prison Bounty Hunters

This component makes the fight against the Planar Prison bounty hunters a bit more difficult. Aawill the Bard is now a Blade and will use spells commensurate with his level. His companions will also be better equipped, and an additional companion may join the fight at higher difficulties.

#### Improved Irenicus

I take the original Tactics fight, with some slight alterations, to give Joneleth "The Shattered One" Irenicus the fight he and the player truly deserve. This is a multi-phase fight that should provide a suitable challenge. To start, instead of summoning generic demons, Jon will shatter himself into multiple fragments and brings forth enemies for each Tear of Bhaal Test in Hell. These enemies will provide their own unique challenges, and will bring forth more minions to aid themselves, depending on the difficulty. 

#### Improved Guarded Compound in the Temple District

This component provides a drastic increase in difficulty for the guardians of Celestial Fury. Enemies will have appropriate gear and spell picks for their levels. Enemies will prepare for your arrival and prebuff, and once you arrive there is no escape to the lower floor until you are victorious.

PLEASE NOTE: This component pairs well with the Forgotten Armament component to add net new items into the game for yet an additional difficulty increase. 

#### Improved Twisted Rune

Enemies in this encounter will behave as characters of their level should with better decision making and gear. Original Tactics controls to reduce player cheese remain in place. Revanek, instead of being naked, will become Wizard Slayer decked out in new gear with this update. To spice things up, I am assuming the upgrades from the Skills and Abilities Wizard Slayer are or will be installed. This means, if EEex is present, Revanek's hits will have a 10% chance of bypassing PfMW and the like and dispelling the target.

#### Gebhard Blucher's Improved Demon Knights

This component makes the Demon Knights at the Demogorgon altar in the Underdark overall better opponents and more of a challenge to the player. 

#### Kensai Ryu's Tougher Kangaxx and Guardians

The tomb of Kangaxx is protected by a new set of guardians above. They are looking to acquire his ring and will kill any they perceive as getting in the way. If SCS is installed, Kangaxx will revert to SCS AI; however, the guardians will still remain.

#### Kensai Ryu's Improved Crypt King

The Crypt King is now more worthy of that name and will summon more undead minions every now and then. I have overhauled the fight mechanics to make it even more challenging than the original Tactics version.

#### Smarter Dragons (EARLY TESTING - COMING SOON)

As Wes stated: "Dragons clearly got the short end of the stick somewhere. They're just not awe-inspiring in BGII. In fact, they're pretty much pushovers, especially with half-decent tactics on your part." We are not playing Dungeons and Demiliches, or Dungeons and Fire Giants, or Dungeons and Mindflayers. The aim of this component is to vasty improve the power and challenge when facing a dragon.

#### Kensai Ryu's Improved Copper Coronet

Simply adds more guards in the Copper Coronet when they go hostile. 

#### Mike Barnes' Improved Small Teeth Pass

Adds three dragons to Small Teeth Pass (AR1700).

WARNING: Reported to be *incompatible* with TDD. 

#### Morpheus562's Improved Drizzt (BGEE)

This makes the BGEE version of Drizzt more formidable. If he goes hostile, he will prioritize attack the player instead of the gnolls. 

#### Morpheus562's Improved Drizzt (BG2EE)

This makes the BG2EE version of Drizzt and his companions more formidable. Additionally, if playing on Insane difficulty or higher he will bring in a familiar mage to aid him. Should the mage be defeated, any gear acquired from the battle will not be taken from the party at a later time. 

#### Tougher Fire Giants

Damage output and difficulty for fire giants is greatly increased.

#### Morpheus562's Tougher Githyanki

Githyanki will now be better equipped, better leveled, and overall pose more of a challenge to the player. 

#### Morpheus562's Tougher Yuan-ti

Yuan-ti will receive a number of immunities, to include some magic resistance (40%) and complete resistance to poison. Additionally, they receive some snake like enhancements to include infravision, faster casting speed, faster weapon speed, and an extra 0.5 apr. Yuan-ti fighters will now be wielding magical scimitars and leather armors.

PLEASE NOTE: With my Skills and Abilities Proficiency overhaul and Forgotten Armament's NWN Style Weapons and Updates to Existing Weapons will greatly increase the deadliness of Yuan-ti fighters. The average Yuan-ti fighter and Greater Yuan-ti will have a crit range of 16-20, and Yuan-ti Elites will have a crit range of 15-20. 

#### More encounters will be added.

### Enemy Improvements - Install AFTER SCS

#### Improve All Enemies Hit Points

There are a couple options for the player to select to increase the HP of all enemies. There is an additional option to adjust enemy HP based on the ini file if the player does not like the pre-defined options. Friendly cast summons will NOT have their HP altered. 

## Special Thanks

- Wes thank you for your permission to update such an amazing mod! I appreciate being a steward of your work, and I hope you find it enjoyable.
- Gebhard Blucher, Kensai Ryu, Xyx, Mike Barnes, and Ishan, thank you for all your amazing work on the original Tactics mod. I hope you too enjoy the work I have put into it.
- Cam for all of your help and assistance. The reasons are many, thank you.
- alaisFcZ for providing the Spanish translation.
- All those who assisted in testing and providing feedback! I appreciate every single one of you for all that you do!

## Further Reading

- [Installation](INSTALL.md)
- [Change Log](CHANGELOG.md)
