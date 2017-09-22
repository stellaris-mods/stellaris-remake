# Steam description

[//]: # (start)
Steam description transliterated from `steam.bbcode` by [our release script](https://raw.githubusercontent.com/stellaris-mods/scripts/master/stlrel).

## **The whole point defense system never made much sense to me, so I started redoing the game in a way that does\. The whole Strike Craft system, Missiles, PD, and Torpedoes has been redesigned :\-)**

## Here's what the addon achieves, in simple terms

* Balances Missiles and Torpedoes\. Remember how Paradox has failed to balance them since release? Well, this mod does it\.
* Balances PD and Strike Craft\. Remember how Strike Craft are completely useless and simply a vanity? Now they are useful, and awesome\.
* Fixes a lot of (but not all) previously awkward fleet combat situtations where ships would fly off to the other side of the solar system to engage military stations and such, by removing components that add \+armor



## Compatibility
This mod is incompatible with pretty much any mod that adds new ship types, or that also reworks the ship combat\.
It is compatible with most other mods, but if they add Aux items or PD items, it will work, but act weird in the ship designer because you will be able to equip PD items on the Fighter/Bomber craft that were not intended\. But then again, so will the AI\.

I recommend ASBM and Ship Power Stations with this mod\. Automated Behavior Adjustment is included, using them both is also fine\.

At the bottom of the description is a list of files the mod overwrites\.

## Primer
Here's what the addon removes:

* Removed all Point Defence and Flak cannons
* Removed all missiles from standard weapon slots (any empire that starts with missiles gets lasers or kinetic instead)
* Removed all Torpedo slots from standard sections, added T\-slots to all bow\-sections
* Replaced all Hangar slots with Large weapon slot (should have replaced them with T slots, probably)
* Removed all Fighter/Bomber strike craft (Hangar) weapons
* Rework all utility components that add \+armor to \+hp instead
* Replaced PD slots from all ship sections and hardcoded ship designs with a Small weapon slot
* Removed target\_weights and use\_ship\_kill\_target=no from all weapons
* Replaced all Aux slots with Small Utility slot


All the above applies to all ships and monsters you meet in game\. All of them have been updated to use the features of this addon properly (I might have forgotten some random ones, please let me know if you see any PD or old\-style strike crafts\.)

The TLDR of what it adds back in:

* Missiles level 1 are unlocked at the start for everyone
* Missiles are moved to the T\-slot
* Every standard bow\-section type now has added T\-slots and utility slots
* All vanilla techs that were used for the removed features have been reworked to grant other things
* All previous Aux slots are now small utility slots
* All armor utility components now add ship hullpoints instead
* Strike Craft Fighter and Bomber designable ship types, spawned automatically from Battleships
* Strike crafts have PD slots that can equip downsized versions of regular weapons, but also the normal point defense weapons\. They are the only kinds of point defense in the game\.



**1\. Ship sections**
All standard bow\-sections are the only sections in the game that have Torpedo slots now\. Everyone has universal access to these slots, always\.

This "balances" them completely, by definition\.

**2\. Missiles**
All missile weapons are now usable in the Torpedo slot exclusively\.

All empires start with missile tech level 1 \+ either kinetic or lasers\.

Torpedoes are the same, you need to research it like before\. I think maybe the Energy torpedoes and Swarmer missiles might be too powerful, but I have not nerfed or changed them yet\.

**3\. Hangars / Old\-style Strike Craft**
All hangar slots and strike craft weapons have been removed from both the standard tech and from all hardcoded ships like Fallen, Extradimensional, Swarm, and so on\.
They have been replaced by Large weapon slots, or Torpedo slots\.

The vanilla strike craft technologies now provide a new galaxy\-wide hangar\-type strike craft autodeploy feature, where any time you engage a hostile fleet a squadron of strike\-craft style fighters/bombers will spawn\. The size of this squadron depends on number of Battleships in the fleet, the cooldown (starts at 150 days), and researched technologies\.

Strike Craft drones spawned by Battleships or other ships have enough fuel to last for 100 days\. After that they will dismantle themselves immediately\. Strike Crafts that you build from your spaceports will be refueled, and never get automatically dismantled\.

**4\. Armor**
I changed all utility components that add armor so that stations can't be buffed up to 150\+\.
The reason I did this is because of the way combat targetting works, and how ships prefer to engage targets with higher armor\. Now, with all stations and such stripped of their capability to get more armor, fleet combat in systems with spaceports and military stations will appear more natural\.
All components that previously added armor now add hull points instead\.
Another change towards making combat more natural was to add 140 base shield points to all civilian type stations, including spaceports\.

## Beta?
This addon is in beta, I really need some feedback on this stuff\.

There's a reason I had to remove the Aux slot and PD slots from all ship types, even though that was not the plan to start out with\.

It's because the Stellaris auto designer does not complete ships within the restrictions authors set on weapons\. So when I added the new PD and Aux slot items to the Strike Crafts, the other ships in the game would get them equipped no matter what I did\.

Paradox knows about this bug since 1\.2\.x, and it has been reported with huge threads on the official forums at least 5 times\. At least 2 times they have said they would fix it, but they only fixed it for the slots on the right side of the designer (computer, sensor, etc)\. Not weapon slots or utility slots\.

This is also apparent if you try NSC (not at the same time as this mod though), where you will see autodesigns (which the AI always uses) equip the HQ station XL weapon on normal ships\. NSC worked around this issue with their December 20, 2016 release; v3\.0\.15, by simply removing the firing arc restrictions on all XL weapons and making them equippable on the HQ (this does obviously lead to ships with XL weapons firing them in all directions\.)

## Replaced files
This addon overwrites the whole world; I have tried to keep it at a minimum, and have \- despite what it may seem \- actually gone to great lengths to prevent overwriting more files than necessary\.
\- Many files in common/component\_templates
\- Almost all files in common/section\_templates
\- common/ship\_sizes/00\_ship\_sizes\.txt
\- Almost all files in common/global\_ship\_designs

## Contacting me
Feel free to start a new discussion topics on any of my addons, or post in the comment section below\. If you want to talk to me directly, I hang out on the [NSC Discord server](https://discord\.gg/K9jUfws)\. Type _@folk_ in the \#modding\-discussion channel and I will see your message\.


[//]: # (stop)
