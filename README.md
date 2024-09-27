# eaey_obrsword
This is a simple English introduction to the Obe Sword module.





This mod is only a weapon mod, and the mod items are the Orb Sword. A meteorite will appear near the Boar King (just hit it with a pickaxe).
(For an already-saved game, you can use the ~ key to c_spawn("obrsword") to obtain it.)
It contains:
1)	A slot for an item,
2)	Energy value [h3](can be dragged and right-clicked to hold)[/h3],
3)	Energy attack,
4)	Eight resonance effects,
5)	Two small skills,
6)	Four elemental skills,
7)	Orb Sword beam,
8)	Configurable attack sound effects, and random triggering of brief battle BGM. 







1. Basic Knowledge

① Item Slot
The Obsidian Sword comes with one item slot that can only hold the seven gems and the flute from the Eternal Continent to generate energy resonance.

② Energy Value
The energy value mainly consists of the maximum value, the current value, the extra maximum value (Extrapower, abbreviated as EP), the initial maximum value is 100, and the subsequent bonus to the extra maximum value is the total maximum value. 

The recovery of energy depends on:

* Normal attacks
* Additional effects provided by gem resonance,
* The passive ability of the Holy Sword, which grants a slow increase in energy value automatically when evil, monsters, and gigantic beasts with evil attributes are present nearby, and automatically dissipates at a rate of 0.3/s when they are not present, and stops when the energy falls below a certain value (influenced by the maximum energy value and the additional energy value).

③ Energy-based normal attacks
The normal attacks of the Orb Holy Sword will come with special effects.
Effect 1: Energy recovery: Each attack will restore a small amount of energy.
Effect 2: Sound effect of light: A brief battle BGM will be played randomly (can be configured whether to enable).
Effect 3: Light plane: The Orb Holy Sword's attack power consists of the base damage of 30 (which can be configured) plus the current energy value and EP-influenced plane damage.

Part 2: Gem Resonance
Introduction: The resonant gems are red, blue, purple, orange, green, yellow, and rainbow (reinsert the Holy Sword into the gem slot to activate resonance). Each gem, in addition to its resonance effect, also provides additional maximum energy EP. Here are the resonance effects of the various gems (the strength of the gems and the order in which they appear are not related):
Red gem
Blue gem
Purple gem
Orange gem
Green gem
Yellow gem
Rainbow gem EP = 15
Effect 1, Burst Burn: Each normal attack will inflict a burning mark on the target, up to a maximum of three, with the last two increasing damage by only 50%. The passive triggers every 1.5 seconds, causing (8+1% CUR) damage (doubling the base damage against insects), and the burning effect lasts for 15 seconds. Each normal attack resets the duration of the mark.
Effect 2, Reborn in Flames: Each normal attack has a 3/8 chance of restoring 3 life points. 
Tips: Each basic attack resets the current burning mark cooldown, so players should move around strategically and control the pace of their damage output. 



Sapphire
EP = 15
Effect 1, Frozen Body: Each basic attack deals 0.5 layer of Chill to the target, consuming 1 point of Energy. This effect is quadrupled for Dragonfly and Lavaworm, consuming 5 points of Energy.
Effect 2, Chilled Body: When the holder's body temperature exceeds 45°C, each basic attack lowers the temperature by 5°C. 



Sapphire EP = 30
Effect 1: Strike Soul: Deals an additional 35 damage with each attack.
Effect 2: Purify Evil: Recovers (1 + 1% MAX) (up to 10) Sanity points with each attack against shadow/monster creatures. 



Orange Topaz EP = 40
Effect 1, Summoning Sand: There is a high probability that small sand spikes (causing 100 damage) will appear under the target's feet with each basic attack.
Effect 2, Walking on Flat Ground: Each basic attack will increase movement speed by 25%, lasting for 5 seconds, and only refresh the duration of the basic attack.
Effect 3, Concentrating Sand: Each successful summoning of sand will repair a random durability of the marble armor/titanite armor/titanite crown worn by the character (25-45/45), and consume a small amount of energy.
Effect 4, Sand Blessing: The shield effect will bring 50% damage reduction. 



Emerald EP = 50
Emerald Resonance provides a 6A passive effect for the same unit, with 3A and 6A producing different effects.
Effect 1, Regeneration: restores a small amount of the holder's life (up to 18 points per cycle) based on their current energy level.
Effect 2, Creation: restores a fixed amount of the wearer's armor durability without conditions and increases their energy slightly. 



Yellow sapphire EP = 80
Effect 1, Minghui: Creates a small light source, this effect does not require equipment, nor does it require a basic attack.
Effect 2: Punishing Evil: Deals random damage with stun effect to creatures/shadow units within a slightly larger area every 2.5 seconds (20-55) 



Rainbow Gemstone EP = 200
Effect 1, Unbiased: Ignores the Fear Aura, this effect does not require equipment or a basic attack.
Effect 2, Majestic: Brings down a blast of radiant energy on the target, units that have been attacked by the user will take additional damage after being hit three times (1.5% MAX). 



[H3] [B] Skill 3: Readability: To switch between skills with the Orb Sword, simply press the J key. 

Small Skill 1: Light Blade Slash
Skill Slot 1
Switching to this skill causes Orb Sword to switch to a ranged weapon, increasing the damage of normal attacks to 120+(affected by current energy). In this state, each attack recovers less energy, and a fixed amount of 12 energy is consumed. 
Skill No. 2: Teleportation
Similar to Grandma's teleportation device, it can be used when your energy is greater than 75, and you can open a portal to a designated location on the mini-map by right-clicking (if it has been explored). Each time you teleport, you will consume [h3] 75 energy, 70 hunger points, and 30san points[/ 






3.2 Elemental Skills (Experience on Your Own)

Preface: Elemental skills can only be unlocked by defeating specific bosses (instant kill does not count)
[h3]Water Element - Water Domain - No Unlock Required[/h3]
Upon activation, the effect is generated for a specified unit, and the domain affects a large number of units within the area.
Reduce the movement speed of the specified unit by 90% for 4 seconds (doubled for shadow time).
Reduce the attack power of units within the area by 50%.
Dissolve all hostile units' aggression towards the user (excluding dragonflies), and restore a large amount of life and mana to the user.
Increase the recruitment time of available units within the area by 480 seconds.
If the target is a gigantic creature or shadow creature, it will first deal a certain amount of damage before dissolving its aggression (the damage is doubled for shadow).
After 10 seconds, the additional purification effect will be generated for dragonflies, Klaus, and toads (the final damage is determined by the distance of movement). 







[h3]Fire Elemental  Fire Sword   Unlock by defeating Dragon Fly[/h3]
Judgment kill after inflicting sustained heavy damage to the target. 



[h3] Wind Elemental   Wind Gust   Unlock by defeating the Elk Goose[/h3]
Releases a large, adhesive tornado that continuously slices nearby units, inflicting damage. 



[h3] Earth Element: Earth Sword   Unlock by defeating Termite Lions[/h3] Summon a large number of sand spikes at the target location and summon four eye towers that persist for 30 seconds around the target. 



Ultimate Skill:
Orb Origin Beam: (with screen effects)
A massive beam will deal multiple hits and knockback to units along its path. 



[H2] Patch Section: 



If you lose access to unlocked elements when loading a save game, you can restore them by using the console (press ~) and entering the following code. ThePlayer.components.obrsword_power:reviseelement()
Patches:
If you lose an unlocked element while loading a save in the game, you can restore it using the console (press ~) and enter the code below.
ThePlayer.components.obrsword_power:reviseelement()[/b]




More content will be added in the update log, feel free to check it anytime.
If you have any suggestions, please feel free to email me at 1992087557@qq.com.
