# V1.1.4.0

**[Special Thanks]** <br>
The team wishes to express our sincere gratitude to the modding community for not only providing our players with new content to enjoy but also new features and utilities that they otherwise would not have access to.

With today’s update in particular, we wish to thank GlockenGerda for their hard work in creating Grim Internals and inspiring the team to incorporate several quality of life features that have proven to be a staple within the playerbase. We hope that these now baseline features will be a boon to all of our players!

**[Deferred Rendering]** <br>
With this patch, you can now toggle Deferred Rendering under the Video Options.

Deferred Rendering utilizes additional graphics memory to reduce total draw calls per frame by around 30% or more. This should result in a decent performance increase, especially at high video settings. Complex scenes, such as Devil’s Crossing and parts of Fort Ikon, should see the largest gains.

With Deferred Rendering also come additional video setting levels: Very High for Reflections and Particles. With Particles set to Very High, you can enjoy awesome lighting effects on various spells and abilities that will make combat at night and in undergrounds especially dynamic!

Note: Deferred Renderring does require DirectX 11, so if you are running DirectX 9, you will not be able to toggle this setting. Deferred Rendering also uses FXAA Anti-Aliasing, so that option becomes a toggle rather than a drop-down when the new renderer is enabled.

**[Update to Game Difficulty]** <br>
With this patch, the base game has received a substantial balancing overhaul of Normal/Veteran and Elite difficulties, over 1800 database records in all!

We felt that, over time, the base game’s difficulty has waned significantly relative to the power growth of player characters, and even compared to the Ashes of Malmouth and Forgotten Gods expansions.

We’ve narrowed the gap between the expansion content and the base game content, meaning that the lower levels should feel more exhilarating to play and the jump between difficulties will be much smoother.

Does this mean the endgame has gotten more difficult? Well, yes and no. No because we focused balancing on the early game (roughly levels 1-60), but yes because we’ve updated old monster and boss encounters to deal damage in line with expansion enemies. All in all, the challenge should feel more consistent!

**[Major New Features]** <br>
* Auto-Loot for Components, Consumables and Crafting Materials is now available! Simply toggle the option in in the Game Options!
* Partial Components that are looted are now automatically merged with other Partial Components in your inventory.
* Monster Health Bars are now available! To enable them, open the Game Options menu and select your desired settings under the HUD tab.
* Monster HUD has been overhauled with updated visuals.
* Game Options menu has been updated with a new tab. The General tab has been split into Gameplay and Interface for better organization, and also cause General was ready to explode with options.
* The Crafting UI now has a Search Bar to filter through your blueprints based on name or specific stats, similar to the Devotion search.
* Owners of the Ashes of Malmouth expansion now have a Search Bar within the Stash, which will highlight items based on your parameters.

**[Shattered Realm]** <br>
* Slathsarr Aethergaze’s poison pools now have a 50% shorter duration in the Shattered Realm.

**[Crucible]** <br>
* You can now select which Crucible map you wish to play, or Random Map, when launching the Crucible.

**[Art]** <br>
* Boneback rats & Rifthounds have received a visual update to bring them up to our modern standards, just as many early game enemies did before them!
* Spell FX override priority has been reversed. Now the last override applied take precedence, meaning item skill modifiers with fx updates (ex. Callidor’s Tempest) will take priority over transmuter visuals (ex. Wrath of Agrivix).
* Updated Spell FX for many projectiles, explosions and ground effects used by player and monster skills.
* Updated Spell FX for many toggled and activated buff skills from masteries and items to reduce blowout and improve visuals.
* Updated FX for Feet trails to reduce blowout.
* Updated FX for Flames of Ignaffar & Transmuters to reduce blowout & improve visuals.
* Updated FX for Olexra’s Flash Freeze to be a little…cooler.
* Updated FX for Panetti’s Replicating Missile.
* Updated FX for Rune of Kalastor & fragments to reduce blowout.
* Updated FX for Sigil of Consumption, sigil texture & Transmuters to reduce blowout & improve visuals.
* Updated FX for Trozan’s Sky Shard to reduce blow-out and improve visuals.
* Updated various basic damage effects.

**[Animation]** <br>
* Adjusted Female idle poses to improve posture and remove issue with loincloths sticking out strangely on armor.

**[Tech]** <br>
* Fixed several issues that caused monster health to desync in Multiplayer (ie. client would see less/more health on a monster than it actually had).

**[Game]** <br>
* Veteran Difficulty now grants a 10% Experience Gain bonus. This bonus is multiplicative with Experience Gain gear.
* Increased Experience Gain on Elite difficulty
* Improved stats on fixed item quest rewards (ex. so that they are more beneficial for the content that follows.
* Reduced Ruined Devotion Shrine requirements on Elite and Ultimate difficulty. With the advent of the Difficulty Skip Merits, we feel that this will make the leveling experience smoother and not make going back to Normal difficulty to grab shrines feel as advantageous.
* All Component Blueprints now generate Complete Components, rather than Partial Components. Required materials updated accordingly.

**[Itemization]** <br>
* Rune Augments - increased Travel Distance on Rush Runes and reduced Travel Distance on Teleport Runes. Increased damage and utility on all Runes.
* All Legendary Shields that deal non-Physical damage have had their base damage changed to the appropriate damage type (ex. a Vitality shield now deals Vitality damage rather than Physical damage)
* **Relic - Annihilation**: added 8% Energy Cost Reduction, removed Cunning. Granted skill is now a proc triggering off attacks, damage and cooldown adjusted accordingly.
* **Relic - Bane**: added 4% Offensive Ability and 4% Attack damage Converted to Health, removed Offensive Ability. Added Attack damage Converted to Health on the skill proc.
* **Relic - Dreeg’s Affliction**: reduced Cooldown and increased damage on the granted skill. With Forgotten Gods, now has additional % Retaliation damage Added to Attack.
* **Relic - Ignaffar’s Combustion**: removed % Attack/Cast Speed
* **Relic - Necrosis**: granted skill now reduces all non-physical Resists by -10%
* **Relic - Nemesis**: increased Defensive Ability Reduction applied by the pet to 150
* **Relic - Oblivion**: granted skill is now spammable, values adjusted accordingly
* **Relic - Uroboruuk’s Reaping**: increased damage on the granted skill
* **Relic - Yugol’s Hunger**: increased damage on the granted skill
* **Faction - Blazerush**: increased % Attack Speed to 22%, replaced bonuses and modifier for Grenado with support for Flame Touched.
* **Faction - Bloodborer**: increased % Attack Speed to 18%, replaced Pierce damage with Bleed damage. Increased Bleed damage modifier for Storm Spread to 120. Replaced Pierce damage modifier for Phantasmal Blades with an 8% Weapon damage modifier.
* **Faction - Corruptian**: added 4% Cooldown Reduction
* **Faction - Hex Launcher**: increased % Cast Speed to 18%
* **Faction - Nightstalker Pendant**: added 100 Frostburn / 3s modifier for Rune of Hagarrad and increased its % Crit damage modifier to 12%. Increased the Frostburn modifier for Ring of Steel to 200 / 3s and increased its % Crit damage modifier to 12%
* **Faction - Rancor**: reduced % Physical Resist to 6%. Reduced % Bleed Resist Reduction modifier for Devouring Swarm to -10% and its Bleed damage modifier to 50. Increased bonus to Shaman Skills to +2 and reduced bonus to Devouring Swarm to +2.
* **Faction - The Desolator**: increased % Attack Speed to 24%, Defensive Ability to 55 and increased bonus to Flashbang to +3
* **Faction - Vampirris**: increased Chaos damage modifier for Reap Spirit to 122-450
* **Faction - Witch’s Moon**: increased Frostburn damage modifier for Ring of Steel to 220, replaced Pierce damage modifier for Rune of Hagarrad with Cold damage
* **Faction - Wrathguard**: increased Pierce damage and % Attack Speed on the granted skill
* **Faction Augment - Ateph’s Promise**: increased Health to 350 and % Defensive Ability to 3%
* **Faction Augment - Malmouth’s Heart**: replaced % Bleed Resist with Health
* **Faction Augment - Solael’s Glare**: replaced % Bleed Resist with % Pierce Resist
* **Faction Augment - Witch’s Black Flame**: replaced % Petrify Resist with % Stun Resist
* Monster Infrequent - increased Skill bonuses on all two-handed Monster Infrequents to +4, if they are not already
* Monster Infrequent - redesigned bonuses on all Monster Infrequent Belts. Each belt now grants +1 to a mastery and offers conversion.
* **Monster Infrequent - Alkamos’ Scythe**: added 15% Chance of 100% Cooldown Reduction modifier for Blitz
* **Monster Infrequent - Alkamos’ Warsword**: added 15% Chance of 100% Cooldown Reduction modifier for Vire’s Might. Increased % of Fire dealt as Cold modifier for Pneumatic Burst and added a 32 Cold damage modifier for it.
* **Monster Infrequent - Basilisk Fang**: added 100% of Physical dealt as Acid modifier for Aegis of Menhir
* **Monster Infrequent - Korvan Eldritch Halberd**: added modifiers for Smite
* **Monster Infrequent - Korvan Storm Halberd**: increased Cooldown Reduction modifier for Primal Strike to -0.7s
* **Monster Infrequent - Packla’s Skins**: increased Vitality damage modifier for Wendigo Totem to 100 and replaced its Run Speed Reduction modifier with 15% Fumble/Projectile Fumble / 2s modifiers
* **Monster Infrequent - Packla’s Visage**: increased % Bleed Resist Reduction modifier for Siphon Souls to -12%
* **Monster Infrequent - Troll Bonecrusher**: added modifiers for Feral Hunger
* **Component - Bloodied Crystal**: reduced % Bleed Resist to 12%

_**Legendary Non-Set Items**_ <br>
* **Amarastan Crusher**: bonuses redesigned around spammable Amarasta’s Blade Burst
* **Arcanum Electrollis**: added Electrocute damage, 30% Electrocute Duration and 45% of Cold dealt as Lightning
* **Brutallax**: increased % Pierce Ratio to 50%, damage adjusted accordingly
* **Cindercore**: increased % Burn Duration to 50% and increased Offensive Ability to 80
* **Cinderplate Girdle**: added 3% Offensive Ability and increased % Crit damage to 7%, reduced Cooldown on the skill proc
* **Conduit of Night Whispers**: added 100% of Acid dealt as Lightning modifier to the Lightning Shadow Strike variant
* **Conduit of Undying Whispers**: updated Blight Fiend variant to be Vitality themed
* **(Mythical) Covenant of the Three**: increased Burn/Bleeding damage and Defensive Ability Reduction on the skill proc
* **Crimson Spike**: reduced % Pierce Ratio to 10%, damage adjusted accordingly, added 13 Vitality damage
* **Deathguard Sigil**: updated skill proc to have more appropriate damage types
* **(Mythical) Decree of Aldritch**: increased Cooldown Reduction for Devastation to -1.2s
* **Dracarris**: added +2 to Flame Touched, removed +1 to Hellfire Mine. Increased % Chance on Kill for the skill proc to 100%.
* **Dreadscorcher**: now deals pure Aether damage, damage adjusted accordingly. Increased bonus to Inquisitor and Arcanist skills to +2. Conversion replaced with Fire dealt as Aether.
* **(Mythical) Eldritch Gaze**: increased Burn/Bleeding damage and Defensive Ability Reduction on the skill proc
* **Embercore Shoulderguard**: added Fire damage, 3% Attack Speed and 25% of Lightning dealt as Fire, increased Burn damage on the skill proc. Removed Physical damage
* **Entropic Coil**: reduced Burn damage on the skill proc
* **Farath’s Cube**: increased % Crit damage to 12%, % Offensive Ability to 4% and % Health to 4% and increased Cold damage modifiers for Flames of Ignaffar and Panetti’s Replicating Missile to 82 and 60, respectively
* **Fateweaver’s Mantle**: skill proc now activates at 45% Health, instead of when Crit, Cooldown adjusted accordingly
* **Fiend’s Resolve**: updated skill proc values
* **Gavel of Ravenous Souls**: replaced Conversion with 45% of Fire dealt as Physical
* **Gildor’s Pulverizer**: increased Skill bonuses to +4, increased Resist Reduction modifier for Grenado to 28 and added a matching modifier for Vire’s Might
* **Gutsmasher**: increased bonus to Soldier Skills to +2 and Skill Bonuses to +4, increased % Attack Speed to 24% and increased % Health to 8%. Increased Bleed damage modifier for Eye of Reckoning to 210.
* **Hellscourge**: increased Offensive Ability to 70, increased All Resist Reduction modifier for Sigil of Consumption to 22 and increased damage on the skill proc
* **Horns of Korvaak**: added Petrify and % Elemental Damage Reduction to the skill proc. Cooldown reduced on the high level version.
* **Judgment of Empyrion**: added % Lightning damage and 15% of Physical dealt as Fire. Updated Conversion to 45% of Chaos dealt as Lightning. Updated values on the granted skill. Removed % Physical damage.
* **Korvan Wyrm**: added +1 to Shaman skills
* **Lifeblaze Mantle**: increased Offensive Ability to 40, added 3% Cast Speed, removed Conversion. Increased Damage and reduced Cooldown on the skill proc.
* **Mark of Consumption**: reduced % Attack damage Converted to Health modifier for Phantasmal Blades to 4% and its Bleed damage modifier to 40
* **Mythical Abyssal Mask**: added 4% Cast Speed
* **Mythical Adversary**: increased bonuses to Class Skills to +2, reduced bonuses to Improved Casing and Shattering Blast	to +2
* **Mythical Aldanar’s Vanity**: increased Offensive and Defensive Ability to 130
* **Mythical Amatok’s Step**: added 26% Aether Resist
* **Mythical Anderos’ Amplifier**: reduced Fire damage modifier for Mortar Trap to 55
* **Mythical Arcanum Electrollis**: added Electrocute damage, 120% Electrocute Duration, 45% of Cold dealt as Lightning and increased Offensive Ability to 90
* **Mythical Bane of the Winter King**: increased bonus to Shaman Skills to +2
* **Mythical Basilisk Claw**: added 12 Acid damage modifier for Blood of Dreeg and increased its Cooldown Reduction modifier to -2.5s. Added 1200 Poison Retaliation / 5s modifier for Blade Barrier and increased its Cooldown Reduction modifier to -2.5s.
* **Mythical Blood Orb of Ch’thon**: added 550 Health and +1 to Shaman Skills. Added % damage bonuses to the granted skill.
* **Mythical Bloodsong**: reduced % Bleed Duration to 33% and reduced Bleed damage on the skill proc
* **Mythical Boneshatter Treads**: increased % Physical Resist to 4% and % Bleed Resist to 28%
* **Mythical Boneweave Girdle**: added 5% Physical Resist, increased Offensive Ability to 110 and increased bonus to Siphon Souls to +3
* **Mythical Boots of Primordial Rage**: added 30% Stun Resist
* **Mythical Brutallax**: increased % Pierce Ratio to 50%, damage adjusted accordingly. Increased Offensive Ability to 88. Adjusted Bleed damage modifier for Amarasta’s Quick Cut to 120 / 2s.
* **Mythical Butcher of Burrwitch**: reduced Bleed damage and reduced Bleed damage on the skill proc
* **Mythical Chilldread Mantle**: increased Offensive Ability to 75, added 30% Stun Resist and reduced Cooldown on the skill proc
* **Mythical Chillflame Evoker**: increased % Attack/Cast Speed to 18%
* **Mythical Codex of Eternal Storms**: increased Offensive Ability to 122
* **Mythical Codex of Lies**: increased % Crit damage modifier for Albrecht’s Aether Ray to 15%
* **Mythical Codex of Truths**: increased Cooldown Reduction modifier for Horn of Gandarr to -2s and increased Lightning damage modifier for Judgment to 90-300
* **Mythical Crimson Spike**: reduced % Pierce Ratio to 10%, damage adjusted accordingly. Added 21 Vitality damage. Increased Attack damage Converted to Health modifier for Ring of Steel to 20% and increased Heal modifier for Wendigo Totem to 3% + 300.
* **Mythical Crown of the Revenant King**: added 4% Attack Speed and increased Vitality damage modifier for Smite to 110
* **Mythical Death’s Reach**: increased Skill bonuses to +4. Added -10% Vitality/Bleed Resist Reduction modifiers for Bloody Pox and Devouring Swarm.
* **Mythical Death Omen**: added +1 to Necromancer skills
* **Mythical Devil’s Cage Hauberk**: increased Health to 900
* **Mythical Deviltongue**: increased % Attack Speed to 18%
* **Mythical Dracarris**: added +2 to Flame Touched, removed +1 to Hellfire Mine. Increased % Chance on Kill for the skill proc to 100% and adjusted its values. Increased % Attack Speed modifier for Summon Hellhound to 22%.
* **Mythical Dread-Mask of Gurgoth**: fixed missing Lightning damage modifier for Mortar Trap
* **Mythical Dreadscorcher**: now deals pure Aether damage, damage adjusted accordingly. Increased bonus to Inquisitor and Arcanist skills to +2 and added +2 to Necromancer skills, increased Skill bonuses to +4. Conversion replaced with Fire dealt as Aether.
* **Mythical Earthshatter Treads**: updated values on the granted skill
* **Mythical Earthsplitter**: reduced Cooldown on the skill proc
* **Mythical Entropic Coil**: reduced Burn damage on the skill proc
* **Mythical Evoker of Elgoloth**: increased bonus to Savagery to +4
* **Mythical Executioner’s Judgment**: increased % Attack Speed to 10% and increaed bonus to Deadly Momentum to +4
* **Mythical Fateweaver’s Mantle**: skill proc now activates at 45% Health, instead of when Crit, Cooldown adjusted accordingly
* **Mythical Fiendscale Jacket**: increased Health to 950, increased damage on the skill proc and added Defensive Ability Reduction to it
* **Mythical Fiendflesh Greaves**: added 350 Health
* **Mythical Fiend’s Resolve**: increased % Attack and % Cast Speeds to 22%, updated skill proc values
* **Mythical Frostdread Cuirass**: increased % Bleed Resist to 40%
* **Mythical Galewind Treads**: added 50% Freeze Resist, removed % Cold Resist
* **Mythical Gavel of Ravenous Souls**: replaced Conversion with 45% of Fire dealt as Physical, added 100% of Vitality dealt as Physical modifier for Siphon Souls
* **Mythical Guardian of Death’s Gates**: increased bonus to Necromancer Skills to +2 and increased bonuses to Bonds of Bysmiel and Field Command to +4
* **Mythical Guillotine**: added 4% Offensive Ability, increased bonus to Class Skills to +2, increased % Bleed Duration to 150%, . Updated the skill proc and increased its activation chance to 50%.
* **Mythical Gutripper**: added +2 to Shaman skills and added a 120 Bleed damage / 1s modifier for Grasping Vines, increased bonuses to Deadly Momentum and Fighting Form to +4
* **Mythical Hagarradian Enforcer**: increased % Attack Speed to 14%
* **Mythical Inashkor’s Head**: increased % Attack and % Cast Speeds to 22%
* **Mythical Inashkor’s Corrupted Head**: increased % Attack and % Cast Speeds to 22%
* **Mythical Judgment of Empyrion**: added % Lightning damage and 15% of Physical dealt as Fire. Updated Conversion to 45% of Chaos dealt as Lightning. Updated values on the granted skill. Removed % Physical damage.
* **Mythical Leviathan**: increased bonus to Amarasta’s Blade Burst to +4. Increased Physical damage modifier for Amarasta’s Blade Burst to 110, adjusted values on the granted skill.
* **Mythical Lifeblaze Mantle**: increased Offensive Ability to 66, added 4% Cast Speed and 4% Physical Resist, removed Conversion. Increased Damage and reduced Cooldown on the skill proc.
* **Mythical Lifegiver Signet**: increased Defensive Ability to 55 and increased Proc Chance on the skill proc to 15%
* **Mythical Korvan Wyrm**: added +2 to Shaman and Inquisitor skills. Increased Physical damage modifier for Primal Strike to 240.
* **Mythical Mark of Calamitous Desires**: reduced Fire damage modifier for Mortar Trap to 80
* **Mythical Mark of Kalastor**: increased Offensive Ability to 85
* **Mythical Mark of Ulzuin**: increased Offensive Ability to 85
* **Mythical Maw of Despair**: added 26 Aether damage modifier for Field Command
* **Mythical Morguul’s Mortality**: added Vitality Decay damage
* **Mythical Murmur’s Kiss**: added 60 Offensive Ability, increased bonus to Lethal Assault to +3 and increased damage on the skill proc
* **Mythical Nadaan’s Reach**: reduced Bleed damage modifier for Ring of Steel to 140 / 3s
* **Mythical Night’s Embrace**: added -6% Cold/Pierce Resist modifiers for Veil of Shadows. Removed % Resist Reduction from the granted skill.
* **Mythical Nightshade’s Reach**: increased damage on the skill proc
* **Mythical Northern Wyrm**: increased Class Skill bonuses to +2
* **Mythical Nosferattis**: added 10% Physical and 35% Bleed Resists for pets, increased Bleed damage for pets to 14 / 3s
* **Mythical Obsidian Juggernaut**: replaced bonus to Fighting Form with +2 to Soldier Skills, increased bonus to Hellfire Mine to +4
* **Mythical Pagar’s Betrayal**: increased % Retaliation damage added to Attack modifier for Flames of Ignaffar to 8%
* **Mythical Pandemic**: added 4% Cooldown Reduction
* **Mythical Pestilence of Dreeg**: added Conversion based on the Plague it rolls
* **Mythical Quillthrower of Dreeg**: increased bonus to Occultist Skills to +2
* **Mythical Rune of Elgoloth**: reduced Lightning damage modifier for Mortar Trap to 1-100 and added 100% of Physical dealt as Lightning modifier for it
* **Mythical Runeguard Greaves**: added 22% Chaos Resist
* **Mythical Shadowflame Mantle**: added 4% Physical Resist, removed % Cold Resist
* **Mythical Shroud of Illusion**: added 25% of Aether dealt as Elemental, replaced bonus to Aura of Conviction with +2 to Aura of Censure
* **Mythical Silverbolt**: increased bonus to All Skills to +3
* **Mythical Skybreach Bulwark**: increased Defensive Ability to 150
* **Mythical Speaker for the Dead**: increased Offensive Ability to 90
* **Mythical Spelldrinker**: replaced bonuses to Blast Shield and Conversion with +3 to Thermite Mine and Arcane Will
* **Mythical Spiritseeker Cord**: added 35% Pierce and Poison Resists for pets
* **Mythical Soullance**: increased bonuses to Skills to +4 and adjusted values on the skill proc
* **Mythical Starfury Emerald**: added 5% Cooldown Reduction
* **Mythical Stonefist Rebuke**: increased Physical damage modifier for Forcewave to 100
* **Mythical Stormbearers**: increased % Vitality Resist to 35%
* **Mythical Stormreaver**: increased bonus to Inquisitor Skills to +2
* **Mythical Stormweave Armor**: added 3% Physical Resist, increased Offensive Ability to 90 and Defensive Ability to 60
* **Mythical Tainted Ruby of Gar’dal**: increased damage on the skill proc and added % Damage Reduction to it
* **Mythical Temporal Arcblade**: increased Skill bonuses to +4
* **Mythical Timewarped Walkers**: added 24% Bleed Resist
* **Mythical Tome of Atonement**: increased % Damage Modified modifier for Dreeg’s Evil Eye to 100%
* **Mythical Turion’s Reprisal**: increased % Retaliation Damage added to Attack modifier for Blackwater Cocktail to 12%
* **Mythical Venomancer’s Guile**: added 25% of Chaos dealt as Acid, increased Acid damage modifier for Bloody Pox to 55
* **Mythical Venomancer’s Raiment**: increased Offensive Ability to 80, updated Conversion to 25% of Elemental dealt as Acid
* **Mythical Venomspine Greaves**: increased Defensive Ability to 80 and updated values on the skill proc
* **Mythical Vestments of the Great Guardian**: added 25% of Chaos dealt as Acid
* **Mythical Vileblood Mantle**: updated the skill proc
* **Mythical Voice of Dreeg**: added 25% of Chaos dealt as Acid
* **Mythical Voidmancer’s Cord**: added 35% Pierce Resist for pets
* **Mythical Voidwalker Footpads**: increased % Chaos and % Vitality Resists to 40%
* **Mythical Vortex of Souls**: added 8% Physical Resist
* **Mythical Watcher of Erulan**: increased % Physical Resist to 16% and % Total Speed to 15% on the granted skill
* **Mythical Whisperer of Secrets**: increased Health to 480 and Offensive Ability to 96
* **Mythical Windshear Greaves**: increased % Physical Resist to 4% and % Poison Resist to 33%
* **Mythical Wraithwalkers**: added 30% Stun Resist
* **Mythical Wrath of Tenebris**: increased bonus to Occultist Skills to +2
* **Mythical Wretched Tome of Nar’adin**: added 45% of Chaos dealt as Acid and increased Poison Duration to 100%. Increased Acid damage modifier for Dreeg’s Evil Eye to 35 and reduced its Poison Duration modifier to 50%
* **Mythical Wyrmscale Footguards**: added 50% Stun and Petrify Resists
* **Nightclaw**: added 4% Cooldown Reduction. Increased Bleed damage to 28, Attack Speed to 18% and increased Bleed damage on the skill proc.
* **Nosferattis**: added 8% Physical Resist for pets
* **Obsidian Juggernaut**: replaced bonus to Fighting Form with +2 to Soldier Skills
* Pack of Treacherous Means has been refocused on its original direction of Pierce damaged ranged play. A new belt, Pack of Treacherous Memes Pack of Deadly Means has been added to the loot pool that enables the dual-wield direction from v1.1.3.0.
* **Pandemic**: fixed unintentionally low % Vitality/Vitality Decay bonuses and increased % Poison/Vitality Decay Duration to 100%
* **(Mythical) Shar’Zul’s Worldeater**: increased bonus to Soldier Skills to +2
* **Shroud of Illusion**: added 25% of Aether dealt as Elemental, replaced bonus to Aura of Conviction with +2 to Aura of Censure
* **Spark of Reality**: increased Chaos damage to 5-39, added 1.2s Duration modifier for Mirror of Ereoctes
* **Spelldrinker**: replaced bonus to Conversion with +3 to Arcane Will
* **Spiritseeker Cord**: added 30% Pierce Resist for pets
* **(Mythical) Soulrend**: increased bonus to Phantasmal Armor to +4, added +2 to Necromancer skills, adjusted values on the skill proc
* **Tainted Ruby of Gar’dal**: increased damage on the skill proc and added % Damage Reduction to it
* **The Butcher of Burrwitch**: reduced Bleed damage and reduced Bleed damage on the skill proc
* **The Guillotine**: increased bonus to Shaman Skills to +2, updated the skill proc and increased its activation chance to 50%
* **Venomancer’s Raiment**: increased Offensive Ability to 50, updated Conversion to 25% of Elemental dealt as Acid
* **Venomtongue Mantle**: increased Health to 405 and increased damage on the skill proc
* **Wyrmscale Footguards**: added 50% Stun Resist

_**Legendary Set Items**_ <br>
* **Allagast’s Masterpiece Set**: increased Lightning damage modifier for Trozan’s Sky Shard to 30-180, reduced Aether damage modifier for Storm Box of Elgoloth to 110
* **Allagast’s Robe**: increased bonus to Shattered Star to +3
* **Allagast’s Stormbinder**: increased Aether damage modifier for Trozan’s Sky Shard to 145
* **Allagast’s Stormgem**: increased bonus to Shattered Star to +3
* **Blightlord’s Hood**: swapped conversion with Shoulders
* **Blightlord’s Mantle**: swapped conversion with Helm
* **Bloodrager’s Frenzy Set**: removed % Crit damage from the skill proc
* **Bloodrager’s Endless Frenzy Set**: removed % Crit damage and reduced % Damage bonuses on the skill proc
* **Bonemonger Set**: added 26 All Resist Reduction / 3s modifier for Smite
* **Bonemonger’s Chestguard**: added 4% Physical Resist and 4% Attack Speed, removed % Vitality Resist
* **Bonemonger’s Hood**: increased % Vitality Resist to 32%
* **Bonemonger’s Shoulderguard**: added +3 to Resilience, removed bonus to Shattering Smash
* **Chillwhisper Set**: reduced Cold damage modifier for Blade Spirit to 155
* **Dark One Set**: added support for Shaman mastery skills throughout the set and its pieces
* **Dark One’s Hood**: increased Vitality damage modifier for Bloody Pox to 66
* **Deathguard Set**: increased % Crit damage modifier for Shadow Strike to 25%
* **Deathmark’s Shadow Set**: reduced % Physical Resist to 10%
* **Mythical Deathmarked Claw**: reduced Attack damage Converted to Health modifier for Whirlwind Death to 8%
* **Deception of Dreeg Set**: added 6% Physical Resist and 50% of Chaos dealt as Acid
* **Mythical Black Gem of Dreeg**: added 25% of Chaos dealt as Acid
* **Demonslayer’s Defense**: reduced % Physical Resist on the granted skill
* **Demonslayer’s Life-Ender**: reduced % Weapon damage and % damage bonus against Chthonics on the skill proc
* **Invoker’s Elements Set**: reduced % Resist Reduction on the skill proc to -15%
* **Invoker’s Will Set**: reduced % Resist Reduction on the skill proc to -15%
* **Korba’s Fury Set**: increased % Physical Resist to 12%, increased Cold damage modifier for Savagery to 35
* **Korba’s Decapitator**: reduced Bleed damage, added Cold damage, added % Attack damage Converted to Health to the skill proc
* **Korba’s Frenzy**: added Bleed damage, added % Attack damage Converted to Health to the skill proc
* **Korba’s Hood**: reduced Cold damage to 8
* **Light’s Guardian Set**: reduced Lightning damage modifier for Storm Box of Elgoloth to 150
* **Mythical Demonslayer’s Defense**: reduced % Physical Resist on the granted skill
* **Mythical Demonslayer’s Life-Ender**: reduced % Weapon damage and % damage bonus against Chthonics on the skill proc
* **Mythical Infernal Knight’s Faceguard**: added 120 Burn / 2s modifier for Judgment
* **Nature’s Avenger Set**: increased % Health Regeneration to 50%
* **Avenger’s Armor**: increased Health Regeneration to 25
* **Avenger’s Crusher**: Increased bonus to Brute Force to +4 and % Attack Speed to 18%. Increased % Weapon damage modifier for Upheaval to 66%. Fixed skill proc not piercing through enemies, swapped its Pierce damage for Physical and reduced its cooldown.
* **Avenger’s Girdle**: increased Health Regeneration to 32
* **Avenger’s Pauldrons**: increased Health Regeneration to 20
* **Pyran’s Ruminations Set**: increased All Resist Reduction modifier for Devastation to 26 and increased Health Regeneration to 100. Reduced Fire damage modifier for Summon Guardian of Empyrion to 100 and reduced its % Resist Reduction modifiers to -8%.
* **Pyran’s Effigy**: increased Burn damage modifier for Devastation to 80, reduced Fire damage modifier for Mortar Trap to 80, removed % Fire Resist Reduction modifier for Summon Guardian of Empyrion
* **Pyran’s Mantle**: added 200 Health
* **Pyran’s Vestments**: fixed missing Energy Regeneration
* **Pyran’s Visage**: added 20% Aether Resist and 4% Physical Resist, removed % Elemental Resist and Health Regeneration. Increased Fire damage modifier for Devastation to 70.
* **Radaggan’s Folly Set**: added 100% of Fire dealt as Acid modifier for Sigil of Consumption and increased its Cooldown Reduction modifier to -1.5s. Replaced bonus to Mark of Torment with +3 to Ill Omen. Replaced modifier for Spectral Binding with -15% Poison Resist Reduction and 180 Acid damage modifiers for Ill Omen.
* **Radaggan’s Gem**: Replaced modifier for Spectral Binding with -15% Poison Resist Reduction, 70 Acid damage and 100% of Cold dealt as Acid modifiers for Ill Omen
* **Radaggan’s Shroud**: replaced bonus to Mark of Torment with +2 to Ill Omen
* **Rage of Agrivix Set**: increased % Fire Resist Reduction modifier for Siphon Souls to -20% and increased the Aether damage modifier for Vindictive Flame to 140
* **Mythical Codex of Agrivix**: added 55 Aether damage modifier for Siphon Souls
* **Mythical Arcane Shard of Agrivix**: replaced bonus to Harbinger of Souls with +2 to Siphon Souls
* **Rotgheist Set**: increased % Weapon damage modifier for Dreeg’s Evil Eye to 60% and increased Acid damage for Vire’s Might to 180
* **Rotgheist Emblem**: increased Vitality damage modifier for Dreeg’s Evil Eye to 33
* **Rotgheist Mask**: replaced % Crit damage with 5% Cooldown Reduction. Replaced modifiers for Dreeg’s Evil Eye with a 20% Crit damage modifier for it. Increased % Attack damage Converted to Health modifier for Primal Strike to 8%.
* **Rotgheist Shoulderguard**: increased % Aether and Bleed Resists to 28%
* **Runebinder’s Gem**: increased Cold damage modifier for Rune of Hagarrad to 46
* **Runebinder’s Hat**: increased Fire damage modifier for Rune of Kalastor to 60
* **Sentinel of the Three Set**: increased % Retaliation added to Attack modifiers for Counter Strike and Vire’s Might to 12% and 24%, respectively
* **Targo’s Craft Set**: increased Internal Trauma damage modifier for Amarasta’s Blade Burst to 260 and reduced its duration to 2s. Added skill proc.
* **Targo’s Mallet**: increased Physical damage and Internal Trauma modifiers for Blade Arc to 70, added 80 Physical damage modifier for Amarasta’s Blade Burst
* **Targo’s Shoulderguard**: added 30% of Elemental dealt as Physical
* **The Cyclone Set**: increased Fire damage modifier for Thermite Mine to 220
* **Cyclone Mark**: reduced Lightning damage modifier for Thermite Mine to 1-150
* **The Korvan Dunefiend Set**: added 22 Acid damage modifier for Blood of Dreeg and removed its Offensive Ability modifier. Added +1.2s Cooldown and 75% Damage modifier modifiers for Shadow Strike and removed its Energy Cost Reduction modifier. Swapped Lightning to Pierce Conversion for Lightning to Acid Conversion on the set and its pieces.
* **Dunefiend’s Mask**: added Health to granted passive skill, added 55 Offensive Ability modifier for Blood of Dreeg
* **Dunefiend’s Blade**: increased % Weapon damage modifier for Shadow Strike to 35% and added -15% Energy Cost modifier for it
* **Dunefiend’s Slicer**: increased % Weapon damage modifier for Shadow Strike to 35% and added -15% Energy Cost modifier for it
* **The Mageslayer Set**: increased Elemental dot modifiers for Flames of Ignaffar to 80
* **Mageslayer’s Armguard**: increased % Cast Speed to 16%
* **The Venomblade Pact Set**: revised set and its items to support 2 masteries, adding support for Occultist. In some cases, skill bonuses were replaced.
* **The Vileblade Pact Set**: revised set and its items to support 3 masteries, adding support for Occultist. In some cases, skill bonuses were replaced.
* **The Voidsoul Set**: added 12-100 Chaos damage modifier for Flames of Ignaffar
* **Trozan’s Mantle**: added 4% Physical Resist, removed % Cold Resist
* **Trozan’s Skybreach Set**: added support for Occultist mastery skills throughout the set and its pieces
* **Mythical Trozan’s Mantle**: added 4% Physical Resist and increased Health to 440, removed % Cold Resist
* **Ulzuin’s Infernal Avatar Set**: reduced % Weapon damage modifier for Canister Bomb to 14%
* **Mythical Ulzuin’s Flamespreader**: removed Fire damage modifier for Canister Bomb and added the Conversion modifier from the Headguard
* **Mythical Ulzuin’s Headguard**: reduced Burn damage modifier for Canister Bomb to 50 and moved its Conversion modifier to the Flamespreader
* **Valguur’s Hunger Set**: added 6% Attack damage Converted to Health, 100 Vitality damage and 100% of Fire dealt as Vitality damage modifiers for Sigil of Consumption. Moved 50 Vitality damage modifier for Storm Totem to Valguur’s Gems.
* **Valguur’s Focus**: increased Vitality damage modifier for Sigil of Consumption to 75
* **Valguur’s Gems**: added 50 Vitality damage modifier for Storm Totem that was originally on the set bonus
* **Virtue’s Light Set**: reduced % Shield Block damage to 15% and Health to 8%
* **Visor of Octavius**: removed % Physical Resist
* **Voidsoul Armor**: updated Conversion to Elemental dealt as Chaos
* **Voidsoul Bulwark**: increased % Chaos/Vitality Resist Reduction on the skill proc to -15%
* **Voidsoul Visage**: added 10% Weapon damage modifier for Flames of Ignaffar

_**Epic Items**_ <br>
* **Anchorite’s Leg Armor**: added 18% Elemental Resist, removed % Fire/Lightning Resists
* **Band of Wandering Souls**: added 15% Aether Resist, removed % Cold Resist
* **Blazeguard Arbiter**: added 25% Elemental Resist and 280 Health, removed % Fire/Lightning Resists
* **Blazethread Sash**: added 200 Health and 24% Elemental Resist, removed % Fire/Lightning Resists
* **Chillmane Mantle**: added 26% Elemental Resist, removed % Cold Resist
* **Chillsurge Ring**: added 15% Elemental Resist, removed % Cold Resist
* **Circlet of Burning Rage**: added 20% Bleed Resist, removed % Fire Resist
* **Desecrator Treads**: added 15% Elemental Resist, removed % Fire Resist
* **Dreadweave Girdle**: added 30% Aether Resist, removed % Cold Resist
* **Empowered Anchorite’s Leg Armor**: added 30% Elemental Resist, removed % Fire/Lightning Resists
* **Empowered Anchorite’s Seal**: added 15% Elemental Resist, removed % Fire Resist
* **Empowered Band of Black Ice**: added 18% Bleed Resist, removed % Cold Resist
* **Empowered Chillsurge Ring**: added 22% Elemental Resist, removed % Cold Resist
* **Empowered Crest of the Black Legion**: added 600 Health, removed % Fire Resist
* **Empowered Guardsman’s Breastplate**: added 25% Elemental Resist, removed % Fire Resist
* **Empowered Guardsman’s Helm**: added 25% Elemental Resist, removed % Lightning Resist
* **Empowered Guardsman’s Spaulders**: added 25% Elemental Resist, removed % Cold Resist
* **Empowered Lorekeeper’s Band**: added 22% Elemental Resist, removed % Lightning Resist
* **Empowered Nighthunter’s Chestguard**: added 20% Elemental Resist, removed % Cold Resist
* **Empowered Twilight Signet**: added 20% Elemental Resist, removed % Cold Resist
* **Empowered Windborne Greaves**: added 15% Aether Resist
* **Faith’s Guard**: added 40% Chaos Resist, removed % Fire/Lightning Resists
* **Frostshard Crown**: added 20% Vitality Resist, removed % Cold Resist
* **Glory of the Silver Knight**: added 30% Bleed Resist, removed % Fire Resist
* **Guardsman’s Breastplate**: added 15% Elemental Resist, removed % Fire Resist
* **Guardsman’s Helm**: added 15% Elemental Resist, removed % Lightning Resist
* **Guardsman’s Spaulders**: added 15% Elemental Resist, removed % Cold Resist
* **Legionnaire’s Triumph**: added 25% Vitality Resist, removed % Fire Resist
* **Lorekeeper’s Band**: added 12% Elemental Resist, removed % Lightning Resist
* **Mythical Anarchy**: adjusted chance of Chaos damage to 25% of 80-160
* **Mythical Anchorite’s Leg Armor**: added 33% Elemental Resist, removed % Fire/Lightning Resists
* **Mythical Anchorite’s Seal**: added 18% Elemental Resist, removed % Fire Resist
* **Mythical Band of Black Ice**: added 18% Bleed Resist, removed % Cold Resist
* **Mythical Band of Wandering Souls**: added 18% Aether Resist, removed % Cold Resist
* **Mythical Blazeguard Arbiter**: added 28% Elemental Resist and 560 Health, removed % Fire/Lightning Resists
* **Mythical Blazethread Sash**: added 350 Health and 26% Elemental Resist, removed % Fire/Lightning Resists
* **Mythical Bonesnap Gavel**: reduced Physical damage to 14-42 and adjusted chance of Internal Trauma damage to 25% of 140 / 5s
* **Mythical Chillmane Mantle**: added 28% Elemental Resist, removed % Cold Resist
* **Mythical Chillsurge Ring**: added 24% Elemental Resist, removed % Cold Resist
* **Mythical Crest of the Black Legion**: added 800 Health, removed % Fire Resist
* **Mythical Desecrator Treads**: added 18% Elemental Resist, removed % Fire Resist
* **Mythical Dreadweave Girdle**: added 33% Aether Resist, removed % Cold Resist
* **Mythical Faith’s Guard**: added 44% Chaos Resist, removed % Fire/Lightning Resists
* **Mythical Frostshard Crown**: added 22% Vitality Resist, removed % Cold Resist
* **Mythical Glory of the Silver Knight**: added 33% Bleed Resist, removed % Fire Resist
* **Mythical Legionnaire’s Triumph**: added 28% Vitality Resist, removed % Fire Resist
* **Mythical Lorekeeper’s Band**: added 24% Elemental Resist, removed % Lightning Resist
* **Mythical Molten Walkers**: added 24% Vitality Resist
* **Mythical Nighthunter’s Chestguard**: added 22% Elemental Resist, removed % Cold Resist
* **Mythical Notched Bone of a Thousand Deaths**: reduced Pierce damage to 28 and reduced % Crit damage on the granted skill
* **Mythical Sacred Hammer of Eternal Wrath**: adjusted chance of Electrocute damage to 25% of 80-160 / 3s
* **Mythical Shadeleather Leggings**: added 30% Elemental Resist, removed % Cold Resist
* **Mythical Shadowfiend’s Cord**: reduced % Pierce and Vitality Resists for pets to 25%
* **Mythical Spinecarver**: reduced Physical damage to 14-42 and adjusted chance of Bleed damage to 25% of 100 / 3s
* **Mythical Spiritcrusher**: reduced Vitality damage to 28
* **Mythical Star of Frozen Skies**: added 28% Vitality Resist, removed % Lightning Resist, reduced % Cold Resist to 45%
* **Mythical Stormtouched Chains**: added 480 Health, removed % Lightning Resist
* **Mythical Vestments of Mourning**: added 30% Chaos Resist, removed % Cold Resist
* **Notched Bone of a Thousand Deaths**: reduced % Crit damage on the granted skill
* **Ring of Valiance**: added 18% Elemental Resist and 44% Pierce Resist, removed % Fire/Lightning Resists
* **Shadeleather Leggings**: added 25% Elemental Resist, removed % Cold Resist
* **Shadowfiend’s Cord**: reduced % Pierce Resist for pets to 20%
* **Signet of Valiance**: added 18% Elemental Resist, removed % Cold Resist
* **Spinecarver**: adjusted chance of Bleed damage to 25% of 50 / 3s
* **Star of Frozen Skies**: added 25% Vitality Resist, removed % Lightning Resist, reduced % Cold Resist to 40%
* **Stormtouched Chains**: added 300 Health, removed % Lightning Resist
* **The Stormserpent Set**: increased Resist Reduction on the skill proc to 20
* **The Triumvirate (all versions)**: added % Elemental Resist, removed % Lightning Resist
* **Vestments of Mourning**: added 28% Chaos Resist, removed % Cold Resist

**[Class & Skills]** <br>
_**Devotion**_ <br>
* **Living Shadow**: reduced Bleed damage

_**Soldier**_ <br>
* **Blade Arc**: normalized animation speed across all weapon groups. Previously, two-handed melee was up to 20% faster than dual-wield/one-handed. All weapon groups now match the two-handed speed.

_**Demolitionist**_ <br>
* **Canister Bomb**: reduced Burn damage scaling with rank
* **Improved Casing**: reduced Internal Trauma damage scaling with rank
* **Flashbang**: increased base chance of Confuse to 33% and reduced its scaling such that it returns to its original value by rank 12.
* **Mortar Trap**: reduced damage scaling with rank
* **The Big One**: increased Damage scaling with rank. Slow now scales with rank.
* **Shattering Blast**: increased Internal Trauma scaling with rank, particularly at ultimate ranks
* **Thermite Mine**: mines are now placed instantly around the target location, rather than thrown, similar to Inquisitor’s Runes.
* **Vindictive Flame**: increased Health Regeneration scaling with rank
* **Ulzuin’s Wrath**: increased base damage

_**Occultist**_ <br>
* **Sigil of Consumption**: added Vitality Decay damage
* **Destruction**: increased Fire damage scaling with rank, particularly at ultimate ranks, added % Vitality damage

_**Nightblade**_ <br>
* **Amarasta’s Blade Burst**: increased Frostburn damage scaling with rank, particularly at ultimate ranks
* **Amarasta’s Quick Cut**: increased base % Weapon damage to 70% and adjusted scaling such that it returns to its original values by rank 8
* **Blade Spirit**: reduced Bleed damage scaling with rank
* **Frenetic Throw**: increased % Weapon damage penalty to -55%
* **Lethal Assault**: reduced Acid/Cold damage scaling with rank to 52 by rank 12, 116 by max ultimate rank.
* **Shadow Strike**: reduced Cooldown to 3.5s, energy cost reduced accordingly. Increased % Weapon damage scaling at ultimate ranks to 385% by max ultimate rank.
* **Nidalla’s Justifiable Ends**: increased Poison damage scaling with rank, particularly at ultimate ranks. Increased Cooldown Reduction scaling at ultimate ranks to -1.8s by max ultimate rank.
* **Nightfall**: Radius now scales with rank, increased base % Weapon damage by 10%, increased Frostburn and Vitality Decay damage scaling with rank

_**Shaman**_ <br>
* **Primal Strike**: reduced base Energy Cost by 10
* **Thunderous Strike**: reduced % Energy Cost Reduction to 55%
* **Torrent**: increased minimum Lightning damage by 20. Increased base % Weapon damage to 18% and reduced its scaling such that it returns to its original value by rank 12.
* **Wendigo Totem**: increased Duration to 15s, reduced base Energy Cost by 10. Increased base Heal to 2% + 60 and adjusted its scaling such that it returns to its original value by rank 12. Increased Vitality damage scaling with rank, particularly at ultimate ranks and added Vitality Decay damage.
* **Blood Pact**: increased Chance of Attack damage Converted to Health to 100% and reduced its values accordingly. Increased Vitality Decay/Bleed Duration scaling at ultimate ranks to 70% by max ultimate rank.

_**Arcanist**_ <br>
* **Arcane Will**: increased % Health Treshold to 75%
* **Fabric of Reality**: added % Damage to Aetherials and Chthonics. Removed % Energy Leech.
* **Iskandra’s Elemental Exchange**: added % Elemental damage from Overload
* **Overload**: added Offensive Ability, moved % Elemental damage to Iskandra’s Elemental Exchange
* **Elemental Balance**: added Elemental Dot Duration
* **Maiven’s Sphere of Protection**: removed Damage Penalty
* **Conversion**: Slow Resist scaling increased to match the other Resists
* **Mental Alacrity**: increased Energy scaling with rank to 1200 by rank 10, 3025 by max ultimate rank. Increased % Cast Speed scaling at ultimate ranks to 18% by max ultimate rank.
* **Reckless Power**: increased Aether damage scaling with rank, added Chance of Stun Retaliation, removed Burn Duration

_**Inquisitor**_ <br>
* **Infernal Purge**: increased % Crit damage scaling with rank to 50% by rank 12, 70% by max ultimate rank
* **Rune of Hagarrad**: reduced Point-Blank damage penalty to 25%

_**Necromancer**_ <br>
* **Harbinger of Souls**: added Vitality damage

_**Oathkeeper**_ <br>
* **Ascension**: reduced % All damage to match the % All Retaliation damage
* **Celestial Presence**: reduced Radius scaling with rank to 4.0 by rank 12, 4.5 by max ultimate rank. Reduced % Resist Reduction to 30% by rank 12, 40% by max ultimate rank.
* **Eye of Reckoning**: reduced % Weapon damage and Physical damage scaling at ultimate ranks
* **Shattering Smash**: increased % Weapon damage by 5% and increased Physical damage scaling with rank
* **Tectonic Shift**: increased % Physical damage scaling with rank to 108% by rank 12, 198% by max ultimate rank, increased Bleed damage scaling at ultimate ranks

