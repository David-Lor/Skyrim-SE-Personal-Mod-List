# Mod List for Skyrim Special Edition

<p align="center">
  <img src="SkyrimLogo.svg" alt="Skyrim Logo" width="30%" height="30%"/>
</p>

Personal mod list for Skyrim SE, focusing on realism and inmersion.

## Index

- [Requirements, tools](#requirements-tools)
- [Menu, UI](#menu-ui)
- [Combat system](#combat-system)
- [Clothing, objects](#clothing-objects)
- [Realism/Inmersion](#realism-inmersion)
- [Random](#random-not-used-for-production-savegames)

## Requirements, tools

- [SKSE64](https://skse.silverlock.org/): required for script-based mods.
- [PapyrusUtil SE](https://www.nexusmods.com/skyrimspecialedition/mods/13048): required by some mods (Locational Damage Stability Patch)
- [ModOrganizer2](https://github.com/ModOrganizer2/modorganizer): Python frontend tool to manage, organize and set load order for installed mods, with compatibility with the [NexusMods](https://www.nexusmods.com/skyrimspecialedition) API. Might change with official NexusMods [Vortex](https://www.nexusmods.com/site/mods/1/?tab=files).
- [Unofficial Skyrim Special Edition Patch](https://www.nexusmods.com/skyrimspecialedition/mods/266): must-have unofficial patch for multiple bugs.
- [Achievements Mods Enabler](https://www.nexusmods.com/skyrimspecialedition/mods/245): bypass the achievement block when using mods.

## Menu, UI

- [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604): improved inventory menu.
- [Clean Menu](https://www.nexusmods.com/skyrimspecialedition/mods/3223/): remove Bethesda logo from intro; remove Mods, Addons, Credits buttons from main menu.
- [A Quality World Map](https://www.nexusmods.com/skyrimspecialedition/mods/5804): graphically improved world map.

## Combat system

- [Wildcat - Combat of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/1368): improved combat system; more difficulty; killmoves.
  - [Realistic Damage Plugin](https://www.nexusmods.com/skyrimspecialedition/mods/1368?tab=files) to equally increase damage dealt and received on higher in-game dificulties. Game difficulty set to Adept.
- [Deadly Combat](https://www.nexusmods.com/skyrimspecialedition/mods/8850): more difficult combat; fast-paced.
- [Mortal Enemies](https://www.nexusmods.com/skyrimspecialedition/mods/4881): improved NPC combat turn rate.
- [Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296): improve arrow animations; enchanted arrows; arrow bleeding damage.
- [TK Dodge](https://www.nexusmods.com/skyrimspecialedition/mods/15309): dodge movements during combat.
- [Modern Brawl Bug Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1473): fixes on brawl fighting (required by Wildcat).
- [Realistic Melee Range](https://www.nexusmods.com/skyrimspecialedition/mods/3378): reduce melee attack range to a realistic level (- ~20%).
- [Locational Damage](https://www.nexusmods.com/skyrim/mods/12615) + [Locational Damage Stability Patch](https://www.nexusmods.com/skyrimspecialedition/mods/22443): port of the original Locational Damage to Skyrim SE. Include locational damage for the game. Used mainly for arrow headshots.
- [VioLens - A Killmove Mod](https://www.nexusmods.com/skyrimspecialedition/mods/668): force killmoves on low-health NPC.
- ~~[Smiley's Combat Realism Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/27879): NPC health standarization; inventory weight cap limit; increased block damage reduction.~~ Conflicting with health levels from Wildcat Realistic Damage Plugin. Block damage reduction not appreciable.

### Targets

- [ ] Player & NPC health shall have realistic values. If possible, one-hit = not kill but wounded, unless wearing armor.
- [ ] Enemies shall block more attacks (since the objective is to make each hit be important). (_Wildcat, Deadly Combat - but won't always block (level depending?)_)
- [ ] Damage reduction while blocking shall be reduced at most as possible (at least avoid instant-kills while player/NPC receives a hit while blocking on the sword).
- [ ] Avoid instant-kills (like all kills shall have a killmove or finisher)
- [ ] Armor to have more effect than just increasing health/reducing damage ([_True Armor?_](https://www.nexusmods.com/skyrimspecialedition/mods/15921))
- [x] Arrows shall be more deadly. Headshots shall be instant-kills (unless wearing -heavy- helmets, but arrows shall bounce and not stick to the head). (_Locational Damage_)

## Realism/Inmersion

Mods featuring real-world realism/inmersion details, not related with combat.

- [iNeed](https://www.nexusmods.com/skyrimspecialedition/mods/645): food, water & sleep needs.
- ~~[Joy of Perspective](https://www.nexusmods.com/skyrimspecialedition/mods/9358): improved first-person view (full body is visible)~~ (have some bugs, specially with AGO).
- [Populated Cities Towns Villages](https://www.nexusmods.com/skyrimspecialedition/mods/2005): add random NPCs to cities, towns & villages.
- [Run For Your Lives](https://www.nexusmods.com/skyrimspecialedition/mods/2272): civilian NPC run to shelter during dragon attacks, instead of fighting them.
- [No Spinning Death Animation](https://www.nexusmods.com/skyrimspecialedition/mods/1432): remove the ridiculous spinning death animation for player and NPC.

## Clothing, objects

- [Cloaks of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6369): new 100 styles of cloaks.
- [Bandolier](https://www.nexusmods.com/skyrimspecialedition/mods/2417): new craftable pouches, bags and bandoliers.
- ~~[Wearable Lanterns](https://www.nexusmods.com/skyrimspecialedition/mods/7560): new craftable wearable, functional lanterns.~~ Skip for now.

### Appearance

- [Belt-Fastened Quivers](https://www.nexusmods.com/skyrimspecialedition/mods/1182): carry the arrow quiver on the belt, rather than on the back.
  - [AGO Belt-Fastened Quivers Support](https://www.nexusmods.com/skyrimspecialedition/mods/24296): compatibility patch to use Belt-Fastened Quivers with Archery Gameplay Overhaul.
- [Open Face Guard Helmets](https://www.nexusmods.com/skyrimspecialedition/mods/13943): city guard helmets expose the guard face. (alternatives: [Semi-Open Guard Helmets](https://www.nexusmods.com/skyrimspecialedition/mods/3077), [Open Faced Guard Helmets](https://www.nexusmods.com/skyrimspecialedition/mods/4994)).

## Random (not used for "production" savegames)

Mods that I would not use for a real main-story savegame, but for trying modding stuff and randomly playing around.

- [Alternate Start - Live Another Life](https://www.nexusmods.com/skyrimspecialedition/mods/272): to start at a certain location, skipping the Helgen intro.
