# GameSettings

* [Comprehensive GameSettings List](https://cs.uesp.net/wiki/Comprehensive_Settings_List)

# Table of Contents

1. [Gameplay](#Gameplay)
	* [Difficulty](#Difficulty)
	* [Level Scaling](#Level-Scaling)
	* [World](#World)
	* [Actors](#Actors)
2. [Combat](#Combat)
	* [Damage](#Damage)
	* [Power Attack](#Power-Attack)
	* [Hand-To-Hand](#Hand-To-Hand)
	* [Knockback](#Knockback)
	* [Block](#Block)
	* [Combat Speak](#Combat-Speak)
	* [Armor](#Armor)
4. [Stealth](#Stealth)
	* [Sneak Damage](#Sneak-Damage)
	* [Sneak Mechanics](#Sneak-Mechanics)
	* [Crime](#Crime)
	* [Lockpicking](#Lockpicking)
5. [Magic](#Magic)
	* [Magicka Cost](#Magicka-Cost)
	* [Spellmaking](#Spellmaking)
	* [Spell Level](#Spell-Level)
	* [Disease](#Disease)
	* [Magic Visuals](#Magic-Visuals)
	* [Uncategorized Magic](#Uncategorized-Magic)
6. [Enchantment](#Enchantment)
	* [Soulgems](#Soulgems)
7. [Player](#Player)
	* [Health](#Health)
	* [Fatigue](#Fatigue)
	* [Magicka](#Magicka)
	* [Skill](#Skills)
	* [Perks](#Perks)
	* [Attributes](#Attributes)
	* [Levels](#Levels)
9. [Speechcraft](#Speechcraft)
	* [Barter](#Barter)
	* [Bribery](#Bribery)
10. [Item](#Items)
	* [Clothing](#clothing)
	* [Repair](#Repair)
	* [Alchemy](#Alchemy)
	* [Wortcraft](#Wortcraft)
11. [NPC](#NPC)
	* [AI](#AI)
	* [Ranged Combat](#Ranged-Combat)
	* [Blink](#Blink)
12. [Movement](#Movement)
	* [Falling](#Falling)
13. [Physics](#Physics)
	* [Arrows](#Arrows)
	* [Death Force](#Death-Force)
	* [Explosion Force](#Explosion-Force)
	* [Buoyancy](#Buoyancy)
14. [Camera](#Camera)
15. [Miscellaneous](#Miscellaneous)
	* [Stars](#Stars)
16. [Unknown Unused and Broken](#Unknown-Unused-and-Broken)
	

## Gameplay

### Difficulty

<details>
<Summary>Difficulty GameSettings</Summary>
	
1. fDifficultyDamageTakenMultiplierNovice
	* Default: -5.00
	* Description: The Damage multiplier for Damage Taken while on Novice Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
2. fDifficultyDamageTakenMultiplierApprentice
	* Default: -2.50
	* Description: The Damage multiplier for Damage Taken while on Apprentice Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
3. fDifficultyDamageTakenMultiplierAdept
	* Default: 0.00
	* Description: The Damage multiplier for Damage Taken while on Adept Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
4. fDifficultyDamageTakenMultiplierJourneyman
	* Default: 1.50
	* Description: The Damage multiplier for Damage Taken while on Journeyman Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
5. fDifficultyDamageTakenMultiplierExpert
	* Default: 2.50
	* Description: The Damage multiplier for Damage Taken while on Expert Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
6. fDifficultyDamageTakenMultiplierMaster
	* Default: 5.00
	* Description: The Damage multiplier for Damage Taken while on Master Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
7. fDifficultyDamageDealtMultiplierNovice
	* Default: -5.00
	* Description: The Damage multiplier for Damage Dealt while on Novice Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
8. fDifficultyDamageDealtMultiplierApprentice
	* Default: -2.50
	* Description: The Damage multiplier for Damage Dealt while on Apprentice Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
9. fDifficultyDamageDealtMultiplierAdept
	* Default: 0.00
	* Description: The Damage multiplier for Damage Dealt while on Adept Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
10. fDifficultyDamageDealtMultiplierJourneyman
	* Default: 1.50
	* Description: The Damage multiplier for Damage Dealt while on Journeyman Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
11. fDifficultyDamageDealtMultiplierExpert
	* Default: 2.50
	* Description: The Damage multiplier for Damage Dealt while on Expert Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	
12. fDifficultyDamageDealtMultiplierMaster
	* Default: 5.00
	* Description: The Damage multiplier for Damage Dealt while on Master Difficulty.
	* Formula: Final Damage = (fDDM * n) + n ; Where n = actual damage, and fDDM is the value of fDifficultyDamageTakenMultiplier<Difficulty>.
	

</details>

### Level Scaling

<details>
<Summary>Level Scaling GameSettings</summary>

1. iLevCreaLevelDifferenceMax
	* Default: 8
	* Description: Leveled Creatures are governed by this setting. A leveled creature list uses the player's level to determine the top potential creature in a list. From that creature, only entries within this game setting's range are used. The default value is 8.

2. iLevItemLevelDifferenceMax
	* Default: 8
	* Description: Leveled Items are governed by this setting. A leveled item list uses the player's level to determine the top potential item in a list. From that item, only entries within this game setting's range are used. The default value is 8.

3. iLowLevelNPCMaxLevel
	* Default: 4
	* Description: When the player level is less than or equal to this value all NPCs are classed as 'low level'. The game assigns reduced health to 'low level' NPCs to make the early part of the game less challenging. 
	
</details>

### World

<details>
<Summary>World GameSettings</summary>
	
3. fRemoveExcessDeadTime
	* Default: 10.0
	* Description: The amount of time between checks to iRemoveExcessDeadCount. Used to remove excess corpses during periods of heavy combat between many actors, to increase performance.

4. iRemoveExcessDeadCount
	* Default: 15
	* Description: The maximum number of dead bodies allowed in the loaded area before they fade out (dissapear).

5. fRemoveExcessComplexDeadTime
	* Default: 2.5
	* Description: The amount of time between checks to iRemoveExcessDeadComplexCount when SetSceneIsComplex is used. Used to remove excess corpses during periods of heavy combat between many actors, to increase performance.

6. iRemoveExcessDeadComplexCount
	* Default: 3
	* Description: The maximum number of dead bodies allowed in the loaded area before they fade out (dissapear) if the SetSceneIsComplex scripting function is used.

7. fPlayerDeathReloadTime
	* Default: 4.00
	* Description: The number of seconds that the game waits after the player dies before bringing up the Load Game menu.

8. fPlayerDropDistance
	* Default: 100.00
	* Description: The distance where the items are placed when dropped from the player's inventory.
	
9. iAllowAlchemyDuringCombat
	* Default: 0
	* Description: This is a true or false setting(1-true or 0-false). Used to determine whether you can mix alchemy potions while engaged in combat.

10. iAllowRechargeDuringCombat
	* Default: 1
	* Description: This is a true or false setting(1-true or 0-false). Used to determine whether you can recharge magic items with soulgems while engaged in combat.
	
11. iAllowRepairDuringCombat
	* Default: 0
	* Description: This is a true or false setting (1-true or 0-false). Used to determine whether you can use repair hammers to fix armor while engaged in combat.

12. iHoursToRespawnCell
	* Default: 72
	* Description: Cells are not respawned on a regular basis. Rather, they are respawned only when the player is entering them If currentTime > lastVisitedTime + iHoursToRespawnCell

13. iMapMarkerVisibleDistance
	* Default: 12000
	* Description: Affects how far you can see locations in compass (Value 0 means no locations in compass).

13. iMapMarkerRevealDistance
	* Default: 1800
	* Description: New locations are revealed (marked on the player's map) when the player moves to within this amount of game units of an unmarked location.

</details>

### Actors

<details>
<Summary>Actor GameSettings</summary>

1. iNumberActorsAllowedToFollowPlayer
	* Default: 6
	* Description: Controls the number of actors allowed to follow the player.
	
2. iNumberActorsInCombatPlayer
	* Default: 10
	* Description: Controls the number of actors in "combat mode" with the player. If there are more agressive NPCs then this setting allows, they will "wait"; i.e. they will hang back.

3. iDeathDropWeaponChance
	* Default: 100
	* Description: This is the chance that a killed NPC will drop their weapon. If this is set to anything less than 100, an NPC will occasionally hold onto their weapon after death. That is, it will be part of the corpse and will have to be taken from the NPCs corpse inventory.
	
4. iAllyHitAllowed
	* Default: 5
	* Description: The maximum number of times that an NPC will tolerate "friendly hits" in combat, from one of the NPC's allies, until the NPC regards the offender as an enemy. The default is 5, meaning an NPC who is the player's ally will regard the player as an enemy after the player hits him or her at least six times. (Unconfirmed)
	
5. iFriendHitAllowed
	* Default: 3
	* Description: The maximum number of times that an NPC will tolerate "friendly hits" in combat until the NPC regards the offender as an enemy. The default is 3, meaning an NPC who is the player's friend in combat will regard the player as an enemy after the player hits him or her at least four times.

6. iActorLuckSkillBase
	* Default: -20
	* Description: One of the two game settings used to determine the Effective Skill Level. At default, Luck adds two effective skill levels for every five points of Luck past 50. 
	* Formula: iActorLuckSkillBase + fActorLuckSkillMult * Luck

7. fActorLuckSkillMult
	* Default: 0.400
	* Description: One of the two game settings used to determine the Effective Skill Level. At default, Luck adds two effective skill levels for every five points of Luck past 50. 
	* Formula: iActorLuckSkillBase + fActorLuckSkillMult * Luck

8. fActorStrengthEncumbranceMult
	* Default: 5.00
	* Description: The number by which a character's strength is multiplied to get their encumbrance limit (how much weight can be carried).
	* Formula: Strength * fActorStrengthEncumbranceMult
	
9. fActorSwimBreathBase
	* Default: 4.000
	* Description: Determines the base length that any actor can stay under water.
	
10. fActorSwimBreathMult
	* Default: 0.300
	* Description: Multiplier for how long an actor can stay underwater
	
11. fActorSwimBreathDamage
	* Default: 0.200
	* Description: Determines the percent of total health damage that occurs per second when you stay underwater too long.
	
12. iVampirismAgeOffset
	* Default: 20
	* Description: This controls the aging of a character that becomes a vampire. The larger the value, the older the vampire will appear. Allows negative values.
	
13. fActorTeleportFadeSeconds
	* Default: 1.000
	* Description: Controls how long an actor will fade in (or out) when going through a load door, or being moved with MoveTo.
	
14. fActorAnimZAdjust
	* Default: 1.800
	* Description: This determines an actor's, including the player character, distance off the ground. The distance is based off the coordinate system in the game, and is for the Z axis. Increasing the value means actors are always higher off the ground than normal.

</details>

## Combat

### Damage

<details>
<Summary>Damage GameSettings</summary>

[Complete Damage Formula](https://en.uesp.net/wiki/Oblivion:The_Complete_Damage_Formula#Modifiable_Settings)

1. fDamageWeaponMult
	* Default: 0.50
	* Description: Adjusting this value alters all weapon damage proportionately.
	* This variable has no effect on spell damage.
	* Example: a value of 1.5 will triple the damage of all weapons, in the game. A sword with 10 damage, will become a 30 damage sword. The altered value will display correctly in the game text.

2. fDamageSkillBase
	* Default: 0.20
	* Description: This value is used in the formula that determines the actual damage done by a weapon. This multiplier is used to determine the damage a weapon will do if the actor has a skill of zero. There are other factors that determine the actual damage done, such as strength, fatigue and fDamageSkillMult.

3. fDamageSkillMult
	* Default: 1.50
	* Description: This value is multiplied times the actor's skill as part of the calculation used to determine how much damage a weapon does in combat. Actors with a skill of 100 would get the full multiplier and actually do more damage than the weapon is rated for by default. Other factors in determining damage done by weapons are strength, fatigue and fDamageSkillBase.

4. fDamageStrengthBase
	* Default: 0.75
	* Description: Used to calculate the damage-multiplier received from attributes. 
	* For BLUNT and BLADE weapons the actor's current Strength is used
	* For MARKSMAN the actor's current agility is used. 
	* Both are capped at 100, meaning that fortifying your strength over 100 won't result in more damage.
	* Formula: fDamageStrengthBase + Attribute/100 x fDamageStrengthMult

5. fDamageStrengthMult
	* Default: 0.50
	* Description: Used to calculate the damage-multiplier received from attributes.
	* For BLUNT and BLADE weapons the actor's current Strength is used
	* For MARKSMAN the actor's current agility is used. 
	* Both are capped at 100, meaning that fortifying your strength over 100 won't result in more damage.
	* Formula: fDamageStrengthBase + Attribute/100 x fDamageStrengthMult

6. fDamageWeaponConditionBase
	* Default: 0.50
	* Description: 
	* Description: Together with fDamageWeaponConditionMult this determines the amount of damage your weapon does based on it's current health.
	* Example: Setting this value to 1 and fDamageWeaponConditionMult to 0 means that weapons will always deal the same amount of damage, regardless of health, up to the point of breaking.

7. fDamageWeaponConditionMult
	* Default: 0.50
	* Description: Together with fDamageWeaponConditionBase this determines the amount of damage your weapon does based on it's current health.
	* Example: Setting this value to 0 and fDamageWeaponConditionBase to 1 means that weapons will always deal the same amount of damage, regardless of health, up to the point of breaking.

8. fDamageToArmorPercentage
	* Default: 9.0
	* Description: Determines how much damage armor receives when used in combat. Might also affect how much damage it receives from the damage armor spell, needs to be tested.

9. fDamageToWeaponPercentage
	* Default: 0.06
	* Description: Determines how much damage a weapon receives when used in combat.
	
10. fCombatHitConeAngle
	* Default: 35.00
	* Description: Is either the range from an actor's center that an attack can be aimed and count as a successful hit, or the vertical/horizontal range of attacks. Either way, a smaller number causes attacks to have to be aimed more accurately at an actor for them to connect. The confusion comes from the fact that, with a number of around 20 or less, attacks that strike the edge of an actor will pass through them without connecting. The number setting seems to represent degrees. A setting of 45, for example, should allow an actor within a 45 degree arc of the crosshair to be struck by the player's attack.
	
</details>

### Power Attack

<details>
<Summary>Power Attack GameSettings</summary>

1. fPowerAttackDelay
	* Default: 0.3000
	* Description: The amount of time the attack button must be held before a power attack will be executed, and also affects how long a power attack takes. 

2. fDamagePowerAttackBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

3. fDamagePowerAttackBackBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

4. fDamagePowerAttackForwardBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

5. fDamagePowerAttackSideBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

6. fDamagePowerAttackStandBonus
	* Default: 3.00
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.



</details>

### Hand-To-Hand

<details>
<Summary>Hand-To-Hand GameSettings</summary>

1. fHandDamageSkillBase
	* Default: 0.00
	* Description: Base Hand to Hand skill value
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)
	
2. fHandDamageSkillMult
	* Default: 1.00
	* Description: Hand To Hand skill multiplier
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)
	
3. fHandDamageStrengthBase
	* Default: 0.0
	* Description: Base Strength attribute value
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)
	
4. fHandDamageStrengthMult
	* Default: 0.75
	* Description: Strength attribute multiplier
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)
	
5. fHandFatigueDamageBase
	* Default: 1.0
	* Description: Base fatigue damage
	* Formula: fHandFatigueDamageBase + fHandFatigueDamageMult x (fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase))
	
6. fHandFatigueDamageMult
	* Default: 0.5
	* Description: Fatigue damage multiplier
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)
	
7. fHandHealthMax
	* Default: 15.0
	* Description: Base maximum unarmed damage (note: actual maximum damage may be higher or lower depending of the other hand-to-hand settings.)
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)
	
8. fHandHealthMin
	* Default: 1.0
	* Description: Minimum unarmed damage
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)
	
9. fHandReachMult
	* Default: 0.6
	* Description: Unarmed reach (note: the default hand-to-hand reach is about 5 feet or 105 units)
	* Formula: fHandHealthMin + (fHandHealthMax - fHandHealthMin) × (Strength / 100 × fHandDamageStrengthMult + fHandDamageStrengthBase) × (HandToHand / 100 × fHandDamageSkillMult + fHandDamageSkillBase)

</details>

### Knockback

<details>
<Summary>Knockback and Stagger GameSettings</summary>

1. fKnockbackAgilBase
	* Default: 1.00
	* Description: When hitting an opponent the victim get's pushed backwards. The speed at which the victim is pushed back is modified by the victim's agility and the damage of the attack. The agility dependency is controlled by fKnockbackAgilBase and FKnockbackAgilMult. The speed at which the victim is pushed backwards decreases towards the end. The pushback does not seem to be applied if the victim get's staggered.
	
2. fKnockbackAgilMult
	* Default: -0.008
	* Description: When hitting an opponent the victim get's pushed backwards. The speed at which the victim is pushed back is modified by the victim's agility and the damage of the attack. The agility dependency is controlled by fKnockbackAgilBase and FKnockbackAgilMult. The speed at which the victim is pushed backwards decreases towards the end. The pushback does not seem to be applied if the victim get's staggered.
	
3. fKnockbackDamageBase
	* Default: 50
	* Description: When hitting an opponent the victim get's pushed backwards. The speed at which the victim is pushed back is modified by the victim's agility and the damage of the attack. The damage dependency is controlled by FKnockbackDamageBase and FKnockbackDamageMult. The speed at which the victim is pushed backwards decreases towards the end. The pushback does not seem to be applied if the victim get's staggered.
	
4. fKnockbackDamageMult
	* Default: 10
	* Description:When hitting an opponent the victim get's pushed backwards. The speed at which the victim is pushed back is modified by the victim's agility and the damage of the attack. The damage dependency is controlled by FKnockbackDamageBase and FKnockbackDamageMult. The speed at which the victim is pushed backwards decreases towards the end. The pushback does not seem to be applied if the victim get's staggered.
	
5. fKnockbackForceMax
	* Default: 512.000
	* Description: The upper cap on how fast the victim can be pushed back. This is likely the same for any kind of power attack, but with the higher damage of the power attack, the pushback effect is also stronger. The pushback effect is not applied if the victim gets staggered by the attack.
	
6. fKnockbackTime
	* Default: 1.0
	* Description: When hitting an opponent the victim get's pushed backwards. This setting sets the duration in seconds for which this movement happens.
	
7. fKnockdownChance
	* Default: 0.3
	* Description: "Knockdown" refers to what is more commonly known as "staggering". This determines the base fraction of all attacks which will stagger their target. For example with the default value of 0.3, 3 out of 10 attacks will stagger their target on average. The chance to stagger the target is further modified by the damage of the attack and the agility of the victim.
	
</details>

### Block

<details>
<Summary>Block GameSettings</summary>

1. fBlockMax
	* Default: 0.7500
	* Description: Limits the maximum effectiveness of the block skill. In simple terms, a value of 0.75 means that a block skill of 100 would reduce damage by 75% when blocking with a shield. A value of 1.0 combined with a block skill of 100 means that you block all damage when using a shield. The actual percentage effectiveness of the block skill is derived from some formula involving fBlockSkillBase, fBlockSkillMult, fBlockMax and, when using a weapon or your hands, fBlockAmountWeaponMult, and fBlockAmountHandToHandMult.

2. fBlockSkillBase
	* Default: 0.0
	* Description: Determines the percent of damage that is disregard when an attack is blocked from block level 0. A value of 1.0 means 100%. This percentage is added to the total amount of block percentage, so with fblockmax at 1.0, a block skill of 75 and this setting at 0.25 100% of the damage will be blocked. Note that the total damage that is blocked is capped by fBlockMax. The damage blocked by hand to hand or just a weapon is also determent by fBlockAmountHandToHandMult and fBlockAmountWeaponMult respectively and by fBlockScoreNoShieldMult.
	
3. fBlockSkillMult
	* Default: 1.0
	* Description: Determines the amount that is added to fBlockSkillBase for every increased level in block. At the default settings the percentage of damage blocked with a shield and without armor value is equal to the block level of the actor. Though it is by default capped at 75.
	
4. fBlockAmountHandToHandMult
	* Default: 0.2500
	* Description: The amount of damage you block when fighting hand-to-hand is governed by your block skill and this setting. This setting reduces the amount of damage blocked when you block with your hand rather than a shield. In other words, a value of 1.0 means that your hand blocks as much damage as a shield, whereas a value of 0.5 means that your hand only blocks half the damage of a shield. Note: the effectiveness of hand-to-hand for blocking is also reduced by FBlockScoreNoShieldMult.
	
5. fBlockAmountWeaponMult
	* Default: 0.50
	* Description: The amount of damage you block with a weapon is governed by your block skill and this setting. This setting reduces the amount of damage blocked when you block with a weapon rather than a shield. In other words, a value of 1.0 means that your weapon blocks as much damage as a shield, whereas a value of 0.5 means that your weapon only blocks half the damage of a shield.


</details>

### Armor

<details>
<Summary>Armor GameSettings</summary>

1. fMaxArmorRating
	* Default: 85.0
	* Description: Determines the maximum amount of armor. This decimal value is used to determine the maximum armor contribution of all equipped items and effects. The default is 85.00. Since armor rating is the percentage of damage withheld from the target, the best that any combination of armor can do is remove 85% of damage done. It would be potentially dangerous to let this value get too close to 100.

	* Fractional values are retained at all times. An actor's health is a floating point value, as are the weapon damage and armor rating. All calculations are made as floats. Every piece of armor contributes it's armor value directly to this value. Every % of shield and fire/shock/frost shield also adds 1 armor. A value of 0 removes the cap entirely (no limit to armor rating).
	
2. fArmorRatingConditionBase
	* Default: 0.0
	* Description: The current (percentage) condition of a piece of armor is multiplied by fArmorRatingConditionMult and added to this. The result is multiplied by the base armor rating of the piece.
	
3. fArmorRatingConditionMult
	* Default: 1.0
	* Description: The current (percentage) condition of a piece of armor is multiplied by this and added to fArmorRatingConditionBase. The result is multiplied by the base armor rating of the piece.
	
4. fArmorRatingBase
	* Default: 0.0
	* Description: This is a multiplier used to scale the armor rating of armor by skill. A skill of 100 Multiplies the armor rating by 1.0. The fArmorRatingBase value sets the lower threshold for skills of 0. The actual value is interpolated between the two. For example, a skill of 50 is 50% of the way between the min and max, which turns out to be 67.5%.
	
5. fArmorRatingMax
	* Default: 1.0
	* Description: This is a multiplier used to scale the armor rating of armor by skill. A skill of 100 Multiplies the armor rating by 1.0. The fArmorRatingBase value sets the lower threshold for skills of 0. The actual value is interpolated between the two. For example, a skill of 50 is 50% of the way between the min and max, which turns out to be 67.5%.

</details>

### Combat Speak

<details>
<Summary>Combat Speak GameSettings</summary>

1. fCombatSpeakAttackChance
	* Default: 0.080
	* Description: The percentage chance that an NPC will utter one of the voices defined on the Combat->Attack tab of the Generic quest while engaged in combat. These voices are used only by NPCs, not by the player. Seems to relate only to the chance of speaking after combat has started. An NPC will always choose one of these voices when combat is initiated.
	
2. fCombatSpeakHitChance
	* Default: 0.2000
	* Description: The percentage chance that an NPC will utter one of the voices defined under the Combat->Hit tab of the Generic quest when hit with a melee or marksman weapon in combat. NPCs will always use one of these voices when they are killed, regardless of this setting. They are not used when the actor is damaged by a spell, unless the spell kills them. Note that the player uses these voices as well. Setting this to 1.0 causes every hit to trigger a voice, as long as the damage done exceeds the value defined in fCombatHitSpeakThreshold. This can be useful for detecting hits against NPCs or the player.
	
3. fCombatSpeakHitThreshold
	* Default: 0.1000
	* Description: Controls the damage (as a percentage of an NPC's total HP) necessary to trigger a combat speech when an NPC is hit by an attack. Setting it to 1.0000 means that NPCs never speak when struck unless the hit kills them. Setting it to a lower value means they can speak when struck by weaker attacks.
	
4. fCombatSpeakPowerAttackChance
	* Default: 1.00
	* Description: The percentage chance that an NPC or the player will utter one of the voices defined under the Combat->Power Attack tab of the Generic quest when executing a power attack. Power Attack voices are never used while the actor is sneaking or weilding a weapon type other than Blade or Blunt.
	
</details>

## Stealth

### Sneak Damage

<details>
<Summary>Sneak Damage GameSettings</summary>

1. fDamageSneakAttackMult
	* Default: 4.0
	* Description: Multiplies the base attack by this value before applying the damage to an enemy. It is activated when a player initiates an attack while in sneak mode, thus the "Sneak Attack x#" message when you perform a sneak attack on an enemy. This value is a base value for sneak attacks and is further modified by a character's sneak skill, weapon type (melee or ranged), attack direction (front, back, side, sleep), and attack type (normal or power). Each of these modifiers has its own setting.

2. fPerkSneakAttackMarksmanNoviceMult
	* Default: 2.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
3. fPerkSneakAttackMarksmanApprenticeMult
	* Default: 3.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
4. fPerkSneakAttackMarksmanJourneymanMult
	* Default: 3.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
5.	fPerkSneakAttackMarksmanExpertMult
	* Default: 3.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
6. fPerkSneakAttackMarksmanMasterMult
	* Default: 3.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
7. fPerkSneakAttackMeleeNoviceMult
	* Default: 4.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
8. fPerkSneakAttackMeleeApprenticeMult
	* Default: 6.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
9. fPerkSneakAttackMeleeJourneymanMult
	* Default: 6.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
10. fPerkSneakAttackMeleeExpertMult
	* Default: 6.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
11. fPerkSneakAttackMeleeMasterMult
	* Default: 6.0
	* Description: Critical strike damage multipliers granted by the Sneak perk for a successful Melee or Ranged Sneak attack.
	
</details>

### Sneak Mechanics

<details>
<Summary>Sneak Mechanic GameSettings</summary>

1. fDetectionTimerSetting
	* Default: 0.300
	* Description: This value represents how often in seconds an actor makes detection checks against all other actors within the max detection distance.

2. fDetectionSneakLightMod
	* Default: -5.000
	* Description: This value is added to the light level on a target during Detection calculations.

3. fDetectionNightEyeBonus
	* Default: 3.000
	* Description: Bonus multiplier to the light level on nearby actors during detection checks.
	
4. fSneakBaseValue
	* Default: -25.000
	* Description: This is the base value that all modifiers are added to for detection. Changing this value alters the fundamental effectiveness of sneaking. Higher values mean it's harder to sneak, lower values mean it's easier to sneak.
	
5. fSneakBootWeightBase
	* Default: 14.000
	* Description: The is the base penalty to sneaking for wearing boots of any sort. The modified weight of the boots is also factored in using fSneakBootWeightMult.
	
6. fSneakBootWeightMult
	* Default: 1.000
	* Description: The is the multiplier to the actor's boot weight used to modify sneaking. Just wearing boots modifies the sneak value, regardless of their weight or type, by the value of fSneakBootWeightBase.
	
7. fSneakMaxDistance
	* Default: 1500.000
	* Description: Maximum distance that an actor will detect another actor in an interior cell. Anything out of this range does not take part in sneak rolls vs. the sneaking actor. E.g. cannot be detected (not even if the sneaking player attacks). While the actor is in an exterior cell, this value is multiplied by fSneakExteriorDistanceMult.
	
8. fSneakExteriorDistanceMult
	* Default: 2.000
	* Description: The maximum distance that detection will operate is different for exteriors and interiors. The interior value is set by fSneakMaxDistance. That value is multipiied by fSneakExteriorDistanceMult to determine exterior ranges for detection.
	
9. fSneakLightMult
	* Default: 1.400
	* Description: This multiplier is applied to all the light based aspects of detection. It is used to regulate the relative weight of light vs. sound vs. skill in calculating the final detection value. The higher the value, the easier an actor detects another based on the light conditions.
	
10. fSneakLostMin
	* Default: -20.000
	* Description: Once detected, the detection value has to fall below this number for the actor to be "lost." This means that the detecting actor breaks combat and no longer searches for the actor or says the warning lines. This functionality only comes into play after the actor has been detected.
	
11. fSneakNoticedMin
	* Default: -20.000
	* Description: An undetected actor is "noticed" when the detection value exceeds this threshhold. Being noticed means that the actor will start to say things (assuming they can talk) that are marked accordingly.
	
12. fSneakRunningMult
	* Default: 1.300
	* Description: Running is noisier than walking. This multiplier is applied to the boot weight and other sound penalties if the actor is running.
	
13. fSneakSeenMin
	* Default: 0.000
	* Description: This is the threshold value at which the actor fades into sight and can be targeted for combat (or anything else) by other actors.When the actor attacked the sneaking actor, the sneaking actor remains visible until the value falls below fSneakLostMin. When the actor did not attack (the actor seeing You is not hostile, You did not attack or steal anything), the sneaking actor remains visible until the value falls below FSneakUnseenMin - this latter part is to be tested and confirmed.
	
14. fSneakSkillMult
	* Default: 0.500
	* Description: This is the multiplier applied to the relative skill values of the actors. It is used to regulate the relative weight of light vs. sound vs. skill in the detection calculations.
	
15. fSneakSleepBonus
	* Default: -10.000
	* Description: Determines the Sneak bonus an actor gets if the target is sleeping.
	
16. fSneakSoundLosMult
	* Default: 1.000
	* Description: This multiplier is applied to the sound portion of the detection system if the actor does not have line of sight (LOS) to the hiding actor.
	
17. fSneakSoundsMult
	* Default: 1.600
	* Description: This multiplier governs the importance of sounds (and sounds only) made during sneaking. The higher it is, the harder the sneaking will be because you have to make less noise. For example, 0 means that sounds have no effect at all, while 1 means that sounds have normal effect.
	
18. fSneakSwimmingLightMult
	* Default: 0.500
	* Description: This multiplier is applied to swimming actors, but only to the light portion of the detection system.
	
19. fSneakTargetAttackBonus
	* Default: 100.000
	* Description: An actor that is the direct target of an attack gets this bonus to detect their attacker.
	
20. fSneakTargetInCombatBonus
	* Default: 25.000
	* Description: Combat is noisy. Any actor in combat, but not in combat with the detecting actor, has this penalty applied for sneaking.
	
21. fSneakUnseenMin
	* Default: 0.000
	* Description: This is the threshold value at which the actor fades out of sight and cannot be targeted for combat (or anything else) by other actors. This is true only however when the actor is trying to sneak around a non-hostile actor. If the actor is hostile, fSneakLostMin is used instead.
	
22. iAICombatMinDetection
	* Default: -50
	* Description: When an actor is in combat, the detection value has to fall below this number for the actor to lose track of their target.

23. iSneakSkillUseDistance
	* Default: 1000
	* Description: If the player is sneaking within this distance from another actor (NPC, creature) and the player is undetected then the player is actively using the sneak skill and it will eventually increase. If there are no actors within this distance of the player then the use of sneak does not count towards increasing the sneak skill.

</details>

### Crime

<details>
<Summary>Crime GameSettings</Summary>

1. fCrimeDispAttack
	* Default: -10.000
	* Description: Witnessing a crime may affect an NPC's disposition to the criminal. This is the modifier to disposition that happens when an NPC witnesses an attack on someone he likes. If the attack is against the NPC, the modifier is multiplied by fCrimeDispPersonal first, which increases the disposition penalty.
	
2. fCrimeDispMurder
	* Default: -50.000
	* Description: Witnessing a crime may affect an NPC's disposition to the criminal. This is the modifier to disposition that happens when an NPC witnesses the murder of someone he likes.
	
3. fCrimeDispPersonal
	* Default: 2.000
	* Description: Witnessing a crime reduces an NPC's disposition toward the criminal. If the NPC is the victim of the crime, the disposition penalty is multiplied by this setting. For example, witnessing an assault is a -10 disposition penalty toward the criminal. However, being the victim of assault is a -20 penalty (-10 time 2.0).
	
4. fCrimeDispPickpocket
	* Default: -25.000
	* Description: Witnessing a crime may affect an NPC's disposition to the criminal. This is the modifier to disposition that happens when an NPC witnesses pickpocking against someone he likes. If the NPC is the one being pickpocketed, the modifier is multiplied by fCrimeDispPersonal first, which increases the disposition penalty.
	
5. fCrimeDispSteal
	* Default: -0.500
	* Description: Witnessing a crime may affect an NPC's disposition to the criminal. This is the multiplier used to modify an NPC's disposition when he witnesses a theft of someone's property that he likes. This value multiplied by the gold value of the item stolen to make the modifier. If the theft is against the NPC, the modifier is multiplied by fCrimeDispPersonal first, which increases the disposition penalty.

6. fCrimeDispTresspass
	* Default: -20.000
	* Description: Witnessing a crime may affect an NPC's disposition to the criminal. This is the modifier to disposition that happens when an NPC witnesses trespassing against someone he likes. If the trespass is against the NPC, the modifier is multiplied by fCrimeDispPersonal first, which increases the disposition penalty.
	
7. fCrimeGoldSteal
	* Default: 0.5000
	* Description: Acts as a multiplier to the value of the stolen item in calculating the fine for theft.
	* Formula: is Crime Gold = itemValue * fCrimeGoldSteal.
	
8. iCrimeAlarmRecDistance
	* Default: 4000
	* Description: This sets the distance from which a crime victim's cries for help can be heard.
	
9. iCrimeDaysInPrisonMod
	* Default: 100
	* Description: This determines the number of days the player have to stay in prison when arrested. To get number of days, player bounty is divided by the value of this setting.
	
10. iCrimeGoldAttackMin
	* Default: 500
	* Description: Sets the minimum bounty level required for guards to rush a player on sight. This is not the level that causes guards to attack.
	
11. iCrimeGoldAttack
	* Default: 40
	* Description: These settings control the fine levied when the player is caught committing a crime.
	
12. iCrimeGoldJailBreak
	* Default: 50
	* Description: These settings control the fine levied when the player is caught committing a crime.
	
13. iCrimeGoldMinValue
	* Default: 50
	* Description: These settings control the fine levied when the player is caught committing a crime.
	
14. iCrimeGoldMurder
	* Default: 1000
	* Description: These settings control the fine levied when the player is caught committing a crime.
	
15. iCrimeGoldPickpocket
	* Default: 25
	* Description: These settings control the fine levied when the player is caught committing a crime.
	
16. iCrimeGoldStealHorse
	* Default: 250
	* Description: These settings control the fine levied when the player is caught committing a crime.
	
17. iCrimeGoldTresspass
	* Default: 5
	* Description: These settings control the fine levied when the player is caught committing a crime.

18. iNumberGuardsCrimeResponse
	* Default: 4
	* Description: This value governs the number of guards that appear when the player commits a crime and it has been reported. If set to 0, no guard appears.

</details>

### Lockpicking

<details>
<Summary>Lockpicking GameSettings</Summary>

1. fLockPickAutoBase
	* Default: 45.00
	* Description: Base chance forcing a lock will work.
	
2. iLockLevelMaxVeryEasy
	* Default: 7
	* Description: The lock levels of Very Easy, Easy, Average, Hard, Very Hard, and Needs a Key are all mapped to numerical values between 0 and 100. These numbers are stored in the game settings listed below. A value of 100 is hard coded to mean "Needs a Key." The specific values are used to calculate a variety of things and should not be changed from their default values.

3. iLockLevelMaxEasy
	* Default: 20
	* Description: The lock levels of Very Easy, Easy, Average, Hard, Very Hard, and Needs a Key are all mapped to numerical values between 0 and 100. These numbers are stored in the game settings listed below. A value of 100 is hard coded to mean "Needs a Key." The specific values are used to calculate a variety of things and should not be changed from their default values.

4. iLockLevelMaxAverage
	* Default: 40
	* Description: The lock levels of Very Easy, Easy, Average, Hard, Very Hard, and Needs a Key are all mapped to numerical values between 0 and 100. These numbers are stored in the game settings listed below. A value of 100 is hard coded to mean "Needs a Key." The specific values are used to calculate a variety of things and should not be changed from their default values.

5. iLockLevelMaxHard
	* Default: 80
	* Description: The lock levels of Very Easy, Easy, Average, Hard, Very Hard, and Needs a Key are all mapped to numerical values between 0 and 100. These numbers are stored in the game settings listed below. A value of 100 is hard coded to mean "Needs a Key." The specific values are used to calculate a variety of things and should not be changed from their default values.

6. iLockLevelMaxVeryHard
	* Default: 99
	* Description: The lock levels of Very Easy, Easy, Average, Hard, Very Hard, and Needs a Key are all mapped to numerical values between 0 and 100. These numbers are stored in the game settings listed below. A value of 100 is hard coded to mean "Needs a Key." The specific values are used to calculate a variety of things and should not be changed from their default values.

</details>

### Pickpocketing

<details>
<Summary>Pickpocketing GameSettings</summary>

1. fPickPocketMaxChance
	* Default: 85.00
	* Description: Maximum chance pickpocketing can have to succeed.
	
2. fPickPocketMinChance
	* Default: 5.00
	* Description: Minimum chance pickpocketing can have to succeed.

</details>

## Magic

### Magicka Cost

<details>
<Summary>Magicka Cost GameSettings</summary>

[Spell Cost](https://cs.uesp.net/wiki/Category:Spell_Cost)

1. fMagicCostScale
	* Default: 1.28
	* Description: Modifies how much spell magnitude affects Magicka cost.

2. fMagicAreaBaseCostMult
	* Default: 0.15
	* Description: Modifies how much spell Area affects Magicka cost.

3. fMagicDurMagBaseCostMult
	* Default: 0.1
	* Description: The spell's Effect Base Cost is multiplied by this value.	

4. fMagicRangeTargetCostMult
	* Default: 1.5
	* Description: If the spell is on Target, the total cost is multiplied by this.

5. fMagicCasterSkillCostBase
	* Default: 0.2
	* Description: The minimum value of skill factor.

6. fMagicCasterSkillCostMult
	* Default: 1.2
	* Description: The caster's effective skill (as a percentage) is multiplied by this value.

</details>

### Spellmaking

<details>
<Summary>Spellmaking GameSettings</summary>

1. fSpellmakingGoldMult
	* Default: 3.00
	* Description: The Magicka cost of a spell is multiplied by this value to determine what the spell costs in Gold to buy or create. For spell merchants this cost is then modified by barter settings.

</details>
	
### Spell Level

<details>
<Summary>Spell Level GameSettings</summary>

1. fMagicSpellLevelApprenticeMin
	* Default: 25.5
	* Description: These values are the base spell costs that separate spells into mastery tiers. Any spell whose base cost is greater than a particular threshold yet below the next threshold is considered to be of a particular tier.

2. fMagicSpellLevelJourneymanMin
	* Default: 62.5
	* Description: These values are the base spell costs that separate spells into mastery tiers. Any spell whose base cost is greater than a particular threshold yet below the next threshold is considered to be of a particular tier.

3. fMagicSpellLevelExpertMin
	* Default: 149.5
	* Description: These values are the base spell costs that separate spells into mastery tiers. Any spell whose base cost is greater than a particular threshold yet below the next threshold is considered to be of a particular tier.

4. fMagicSpellLevelMasterMin
	* Default: 399.5
	* Description: These values are the base spell costs that separate spells into mastery tiers. Any spell whose base cost is greater than a particular threshold yet below the next threshold is considered to be of a particular tier.

</details>

### Disease

<details>
<Summary>Disease GameSettings</summary>

1. fMagicDiseaseTransferBase
	* Default: 0.0
	* Description: The base chance that an actor will contract a disease when struck by an infected attacker. Increasing this value allows actors with 100% disease resistance to contract diseases; decreasing it gives 100% protection against disease to actors with less than 100 disease resistance.

2. fMagicDiseaseTransferMult
	* Default: 0.250
	* Description: This value is multiplied by an actor's Resist Disease attribute to determine the chance that the actor will contract a disease when struck by an infected attacker.

3. fMagicSunDamageSunHiddenScale
	* Default: 0.20
	* Description: Modifer used in the calculation of taking damage from the sun. This setting reduces damage to the character should the direct rays of sun be hidden behind terrain or clouds.

4. fMagicSunDamageWaterScale
	* Default: 0.20
	* Description: Used in the calculation for taking damage from the sun. This setting will reduce sun damage for being submerged under water.

</details>

### Magic Visuals

<details>
<Summary>Magic Visuals GameSettings</summary>

1. fMagicLightForwardOffset
	* Default: 22.0
	* Description: When casting a light spell, this is the distance in front of the player that the center of the light will be placed.

2. fMagicLightHeightOffset
	* Default: -96.0
	* Description: When casting a light spell, this is the height distance above the player that the center of the light will be placed.

3. fMagicNightEyeAmbient
	* Default: 0.75
	* Description: Affects Magic Night-Eye brightness. Higher value means brighter view.

4. fShockCastVOffset
	* Default: -5
	* Description: This is the angle that the bolts come from the caster's hand. Negative values angle down, positive angles up. Unsure of the usefulness of changing this.
	
5. fShockBoltsRadius
	* Default: 48
	* Description: How wide the bolts are in a shock damage spell.
	
6. fChameleonMaxRefraction
	* Default: 1.000
	* Description: The chameleon visual is an applied refraction to the model. The degree of refraction is specified by two variables fChameleonMaxRefraction and fChameleonMinRefraction. The maximum refraction value is mapped to a chameleon setting of 1. The minimum refaction value is mapped to a chameleon setting of 100. Values that exceed 1.0 run the risk of having certain polygons become totally transparent. In practice, there is not much visual difference in the scale.
	
7. fChameleonMinRefraction
	* Default: 0.0100
	* Description: The chameleon visual is an applied refraction to the model. The degree of refraction is specified by two variables fChameleonMaxRefraction and fChameleonMinRefraction. The maximum refraction value is mapped to a chameleon setting of 1. The minimum refaction value is mapped to a chameleon setting of 100. Values that exceed 1.0 run the risk of having certain polygons become totally transparent. In practice, there is not much visual difference in the scale.

</details>

### Uncategorized Magic

<details>
<Summary>Uncategorized Magic GameSettings</summary>

1. fMagicLevelMagnitudeMult
	* Default: 0.250
	* Description: Multiplier for level-based magic effects like Turn Undead, Frenzy, Calm, Command etc. This is the reason why you can't create any spells with a level-magnitude over 25. The maximum magnitude of any spell that is created by spellmaking is limited to 100. This multiplier will turn 100 into 25. Change the value to 1 to allow the creation of level-based spell to effect target's up to level 100. Changing it will alter every existing spell/enchantment.

2. iMagnitudeLevelAffectsAll
	* Default: 25
	* Description: This value affects the level at which spells with a magnitude (command humanoid, calm, etc.) will affect creatures of all levels. The default setting is 25 (since the in-game spellmaking/enchanting altars stop at magnitude 25).

3. fMagicUnitsPerFoot
	* Default: 22.0
	* Description: Oblivion uses a coordinate system with 'units' as the base form of measurement. When calculating areas of effect, Oblivion uses fMagicUnitsPerFoot to convert the 'feet' attribute of the area of effect into the equivalent units. The default value is 22.0000.

4. iMaxPlayerSummonedCreatures
	* Default: 1
	* Description: This is the number of summoned creatures the player can control at any one time.
	
</details>

## Enchantment

<details>
<Summary>Enchantment GameSettings</summary>

1. fMagicCEEnchantMagOffset
	* Default: 5.0
	* Description: Value added to constant enchantment magnitude.
	* Formula: Magnitude = (SoulGemNumber 	* Constant Effect Enchantment Factor 	* Base Cost) + fMagicCEEnchantMagOffset

2. fEnchantmentGoldMult
	* Default: 10.0
	* Description: Multiplier used to calculate the amount of gold to be paid for an enchantment.

3. fEnchantmentPointsMult
	* Default: 0.40
	* Description: Multiplier used to calculate the gold value added to an enchanted item. 
	* Formula: Max_Charge 	* fEnchantmentPointsMult + Cost_to_Use 	* fEnchantmentEffectPointsMult

4. fRechargeGoldMult
	* Default: 2.0
	* Description: Multiplier used to calculate the recharge cost for any enchanted item when taken to an enchanter service.
	* Formula: (Charge_Max-Charge_Current) 	* fRechargeGoldMult

</details>

### Soulgems

<details>
<Summary>Soulgems GameSettings</summary>

1. iSoulLevelValuePetty
	* Default: 150
	* Description: Charge Provided by Petty Soulgems

2. iSoulLevelValueLesser
	* Default: 300
	* Description: Charge Provided by Lesser Soulgems

3. iSoulLevelValueCommon
	* Default: 800
	* Description: Charge Provided by Common Soulgems

4. iSoulLevelValueGreater
	* Default: 1200
	* Description: Charge Provided by Greater Soulgems

5. iSoulLevelValueGrand
	* Default: 1600
	* Description: Charge Provided by Grand Soulgems

6. fEnchantPettyLimit
	* Default: 15.0
	* Description: The maximum calculated Enchantment value. I.E. the Magicka limit for a single strike on a weapon.

7. fEnchantLesserLimit
	* Default: 25.0
	* Description: The maximum calculated Enchantment value. I.E. the Magicka limit for a single strike on a weapon.

8. fEnchantCommonLimit
	* Default: 40.0
	* Description: The maximum calculated Enchantment value. I.E. the Magicka limit for a single strike on a weapon.

9. fEnchantGreaterLimit
	* Default: 60.0
	* Description: The maximum calculated Enchantment value. I.E. the Magicka limit for a single strike on a weapon.

10. fEnchantGrandLimit
	* Default: 85.0
	* Description: The maximum calculated Enchantment value. I.E. the Magicka limit for a single strike on a weapon.

</details>

## Player

### Health

<details>
<summary>Health GameSettings</Summary>

[Health](https://cs.uesp.net/wiki/Health)

1. fPCBaseHealthMult
	* Default: 2.0
	* Description: Affects the health of the player at the start of the game. Value is multiplied by the player's endurance to calculate starting health. Has no effect on health when the player levels up unless the player gains Endurance that level, in which case the player's base health will be recalculated according to this setting.
	* Formula: Endurance * fPCBaseHealthMult * fStatsHealthStartMult
	
2. fStatsHealthStartMult 
	* Default: 1.0
	* Description: Multiplier used in the Base Health calculation
	* Formula: Endurance * fPCBaseHealthMult * fStatsHealthStartMult

3. fStatsHealthLevelMult
	* Default: 0.1
	* Description: The number by which the player's endurance is multiplied to calculate the amount of health to be added when the character levels up. The value produced is rounded down to the nearest whole number. If this value is set to 0.0, character health will be based directly on endurance, with no level bonuses. This only affects the player.
	* Formula: Endurance * fStatsHealthLevelMult

</details>

### Fatigue

<details>
<summary>Fatigue GameSettings</Summary>

[Fatigue GameSettings](https://cs.uesp.net/wiki/Fatigue_Game_Settings)

1. fFatigueBase
	* Default: 1.0
	* Description: Base impact of low fatigue

2. fFatigueMult
	* Default: 0.5
	* Description: Multiplier for impact of low fatigue

3. fFatigueReturnBase
	* Default: 10.0
	* Description: Base fatigue regenerated per second

4. fFatigueReturnMult
	* Default: 0.0
	* Description: Fatigue regenerated per second endurance multiplier

5. fFatigueRunBase
	* Default: 8.0
	* Description: Fatigue burned per second when running

6. fFatigueRunMult
	* Default: 0.0
	* Description: Fatigue burned per second when running encumberance multiplier

7. fFatigueJumpBase
	* Default (OG): 30.0
	* Default (RE): 14.0
	* Description: Fatigue burned by jumping

8. fFatigueJumpMult
	* Default: 0.0
	* Description: Fatigue burned by jumping encumberance multiplier

9. fFatigueCastBase
	* Default: 1.0
	* Description: Fatigue burned by spell casting

10. fFatigueCastMult
	* Default: 0.0
	* Description: Fatigue burned by spell casting multiplier, depended on the magic cost for the spell.

11. fFatigueAttackWeaponBase
	* Default: 7.0
	* Description: Fatigue burned by attack

12. fFatigueAttackWeaponMult
	* Default: 0.1
	* Description: Fatigue burned by attack weapon weight multiplier

13. fFatigueBlockBase
	* Default: 0.0
	* Description: Fatigue burned by block base

14. fFatigueBlockMult
	* Default: 1.0
	* Description: Fatigue burned by block skill/100 multiplier

15. fFatigueBlockSkillBase
	* Default: 20.0
	* Description: Fatigue burned by block base

16. fFatigueBlockSkillMult
	* Default: 0.0
	* Description: Fatigue burned by block skill multiplier

17. fPowerAttackFatiguePenalty
	* Default: 5.0
	* Description: Fatigue burned by a power attack multiplier

18. fMarksmanFatigueBurnPerSecond
	* Default: 15.0
	* Description: Fatigue burned per second when bow drawn by novice marksman

19. fMarksmanFatigueBurnPerShot
	* Default: 5.0
	* Description: Fatigue burned per shot (by novice marksman???)

20. iMarksmanFatigueBurnPerSecondSkill
	* Default: 20
	* Description: Unknown. Does not define max skill below which fMarksmanFatigueBurnPerSecond takes affect.

21. fPerkJumpFatigueExpertMult
	* Default: 0.5
	* Description: Acrobatics Perk multiplier for fatigue burn when jumping

22. fPerkAthleticsNoviceFatigueMult
	* Default: 1.0000
	* Description: Applies when actor's Athletics skill is less than iSkillApprenticeMin.

23. fPerkAthleticsApprenticeFatigueMult
	* Default: 0.7500
	* Description: Applies when actor's Athletics skill ranges from iSkillApprenticeMin to iSkillJourneymanMin.

24. fPerkAthleticsJourneymanFatigueMult
	* Default: 0.5000
	* Description: Applies when actor's Athletics skill ranges from iSkillJourneymanMin to iSkillExpertMin.

25. fPerkAthleticsExpertFatigueMult
	* Default: 0.2500
	* Description: Applies when actor's Athletics skill ranges from iSkillExpertMin to iSkillMasterMin.

26. fPerkAthleticsMasterFatigueMult
	* Default: 0.0000
	* Description: Applies when actor's Athletics skill is greater than or equal to iSkillMasterMin.

</details>

### Magicka

<details>
<Summary>Magicka GameSettings</Summary>

1. fPCBaseMagickaMult
	* Default: 1.0
	* Description: Used to calculate the player's magicka from intelligence.

2. fMagickaReturnBase
	* Default: 0.75
	* Description: Base value for magicka regeneration rate.
	* Formula: MagickaRegenRate = 0.01 	* (fMagickaReturnBase + fMagickaReturnMult 	* Willpower) 	* TotalMagicka

3. fMagickaReturnMult
	* Default: 0.020
	* Description: Multiplier used to calculate magicka regeneration rate.
	* Formula: MagickaRegenRate = 0.01 	* (fMagickaReturnBase + fMagickaReturnMult 	* Willpower) 	* TotalMagicka

</details>

### Skills

<details>
<Summary>Skills GameSettings</Summary>

1. fTrainingCostMult
	* Default: 10.0
	* Description: Modifies the cost of training. A higher value means higher training costs.

2. iTrainingSkills
	* Default: 5
	* Description: This is the limit of training sessions a player can receive per level.
	
3. fSkillUseExp
	* Default: 1.5000
	* Description: Controls the amount of experience needed to gain a level in any skill. Higher values of this setting require exponentially more experience for skills to increase. This affects experience requirements at all skill values, but will have most impact for high skill values.
	* Formula: The experience required to increase a skill is proportional to: fSkillUseFactor x skillValue ^ fSkillUseExp
	* This is then multiplied by fSkillUseMajorMult or fSkillUseMinorMult. For skills of the player's specialization, it is then multiplied by fSkillUseSpecMult.
	* Reloading a saved game after changing this value will affect the amount of current experience in every skill.
	
4. fSkillUseFactor
	* Default: 0.3500
	* Description: Controls the amount of experience needed to gain a level in any skill, with higher values requiring more experience per level, and lower values requiring less experience per level. This is a linear multiplier.
	
5. fSkillUseMajorMult
	* Default: 0.750
	* Description: Modifies the number of times you need to use one of your 7 major skills in order to get a skill increase. The base number of uses depends on the level of the skill and other (unknown) factors.
	
6. fSkillUseMinorMult
	* Default (OG): 1.2500
	* Default (RE): 0.875
	* Description: Modifies the number of times you need to use one of your 14 minor skills in order to get a skill increase. The base number of uses depends on the level of the skill and other (unknown) factors. A higher value means the skill has to be used more to get an increase.
	
7. fSkillUseSpecMult
	* Default: 0.75
	* Description: Modifies the speed that a skill, if within the chosen specialization, increases. The three specializations are Stealth, Combat, and Magic. Lower values represent increased leveling speed.
	
8. iSkillApprenticeMin
	* Default: 25
	* Description: These values define the minimum skill level required to recieve skill perks. These values apply to all skills. Spells and enchantments are not included in this calculation.
	
9. iSkillJourneymanMi
	* Default: 50
	* Description: These values define the minimum skill level required to recieve skill perks. These values apply to all skills. Spells and enchantments are not included in this calculation.
	
10. iSkillExpertMin
	* Default: 75
	* Description: These values define the minimum skill level required to recieve skill perks. These values apply to all skills. Spells and enchantments are not included in this calculation.
	
11. iSkillMasterMin
	* Default: 100
	* Description: These values define the minimum skill level required to recieve skill perks. These values apply to all skills. Spells and enchantments are not included in this calculation.

</details>

### Perks

<details>
<Summary>Perks GameSettings</Summary>

1. iPerkMarksmanParalyzeChance
	* Default: 5
	* Description: The percent chance of how often a paralyzing attack can be made with a bow. Requires Master Marksman. 
	
2. iPerkMarksmanKnockdownChance
	* Default: 5
	* Description: The percent chance of knocking down their opponent with an arrow. Requires Expert Marksman. 

3. iPerkHandToHandBlockRecoilChance
	* Default: 25
	* Description: The percent chance of an opponent recoiling after striking a character defending with their Hand-To-Hand skill.

4. iPerkExtraBarterGoldMaster
	* Default: 500
	* Description: The amount of extra gold a merchant will have to barter with a Master of the mercantile skill.

5. iPerkBlockStaggerChance
	* Default: 25
	* Description: The percent chance of staggering their opponent by blocking. Requires Expert Block.

6. iPerkBlockDisarmChance
	* Default: 5
	* Description: The percent chance of disarming their opponent by blocking. Requires Master Block.

7. iPerkAttackDisarmChance
	* Default: 5
	* Description: The percent chance of disarming their opponent by Side-Attacking. Requires Journeyman Blade or Blunt.

</details>

### Attributes

<details>
<Summary>Attributes GameSettings</Summary>

1. fAttributeClassPrimaryBonus
	* Default: 5.000
	* Description: How much an attribute increases when it is selected as the first favored attribute for a class.
	
2. fAttributeClassSecondaryBonus
	* Default: 5.000
	* Description: How much an attribute increases when it is selected as the second favored attribute for a class.
	
</details>

### Levels

<details>
<Summary>Levels GameSettings</Summary>

1. iLevelUpSkillCount
	* Default: 10
	* Description: Number of skill increases necessary to advance to next level.

</details>

## Speechcraft

### Barter

<details>
<Summary>Barter GameSettings</Summary>

1. fBarterBuyBase
	* Default: 300.000
	* Description: Offset added to the value of items sold by merchants.

2. fBarterBuyMult
	* Default: 9.9000
	* Description: How dramatically the difference in the merchants and players merchantile skill affects the price.

3. fBarterDispBase
	* Default: 1.5000
	* Description: Used to control how much effect the mechant's disposition has.

4. fBarterHaggleBase
	* Default: 5.0000
	* Description: Affects the maximum haggle value the merchant will accept.

5. fBarterHaggleCurve
	* Default: 0.5500
	* Description: Affects the maximum haggle value the merchant will accept.

6. fBarterHaggleDispMult
	* Default: 0.5000
	* Description: How much influence the merchant's disposition to the player has on the maximum haggle value the merchant will accept.

7. fBarterHaggleMax
	* Default: 40.0000
	* Description: Limits the total effect haggling can have on the price.

8. fBarterSellBase
	* Default: -20.0000
	* Description: Offset added to the value of items sold to merchants.

9. fBarterSellMult
	* Default: 5.0000
	* Description: How dramatically the difference in the merchants and players merchantile skill affects the price.

10. iMerchantRespawnDay1
	* Default: 0
	* Description: Vendors restock their wares based upon what day of the week it is. Each day is represented as a number, beginning with 0 as Sunday/Sundas and ending with 6 as Saturday/Loredas. As there are only two MerchantRespawnDay entries, venddors can thus only restock their wares twice a week.

11. iMerchantRespawnDay2
	* Default: 3
	* Description: Vendors restock their wares based upon what day of the week it is. Each day is represented as a number, beginning with 0 as Sunday/Sundas and ending with 6 as Saturday/Loredas. As there are only two MerchantRespawnDay entries, venddors can thus only restock their wares twice a week.

</details>

### Bribery

<details>
<Summary>Bribery GameSettings</summary>

1. fBribeCostCurve
	* Default: 1.5000
	* Description: Controls how steep the non-linear increase of the price will be, as determined by the actors' Speechcraft scores.
	
2. fBribeCurve
	* Default: 0.7500
	* Description: Controls how steep the non-linear increase of the disposition bonus will be.
	
3. fBribeNPCLevelMult
	* Default: 0.1000
	* Description: Determines how much weight the NPC's level has relative to the player's level.
	
4. fBribeScale
	* Default: 1.0000
	* Description: A global multipler that increases or decreases all bribe costs proportionally (1.0 is 100% of normal, 2.0 is 200% of normal, etc.).
	
5. fBribeSpeechcraftMult
	* Default: 0.0300
	* Description: Determines how much impact the relative Speechcraft values have compared to the actor's levels.
	
</details>

## Items

### Clothing

<details>
<Summary>Clothing GameSettings</Summary>

1. fClothingArmorBase
	* Default: 0.000
	* Description: One of several settings that control the "clothing value" returned by GetClothingValue. This is the multiplier for the monetary value of any jewelry worn.
	
2. fClothingArmorScale
	* Default: 0.250
	* Description: One of several settings that control the "clothing value" returned by GetClothingValue. This is the multiplier for the monetary value of any jewelry worn.
	
3. fClothingBase
	* Default: 0.000
	* Description: One of several settings that control the "clothing value" returned by GetClothingValue. This is the multiplier for the monetary value of any jewelry worn.
	
4. fClothingClassScale
	* Default: 3.000
	* Description: One of several settings that control the "clothing value" returned by GetClothingValue. This is the multiplier for the monetary value of any jewelry worn.
	
5. fClothingJewelryBase
	* Default: 5.0000
	* Description: One of several settings that control the "clothing value" returned by GetClothingValue. This is the multiplier for the monetary value of any jewelry worn.
	
6. fClothingJewelryScale
	* Default: 0.1000
	* Description: One of several settings that control the "clothing value" returned by GetClothingValue. This is the multiplier for the monetary value of any jewelry worn.
	
</details>

### Repair

<details>
<summary>Repair GameSettings</Summary>

1. fRepairArmorerBase
	* Default: 0.0
	* Description: Determines base amount of health repaired per swing of repair hammer.
	* Formula: fRepairArmorerBase + (Armorer skill * fRepairArmorerMult) + (Strength * fRepairStrengthMult)
	
2. fRepairArmorerMult
	* Default: 1.0
	* Description: Determines base amount of health repaired per swing of repair hammer.
	* Formula: fRepairArmorerBase + (Armorer skill * fRepairArmorerMult) + (Strength * fRepairStrengthMult)
	
3. fRepairStrengthMult
	* Default: 0.1
	* Description: Determines base amount of health repaired per swing of repair hammer.
	* Formula: fRepairArmorerBase + (Armorer skill * fRepairArmorerMult) + (Strength * fRepairStrengthMult)
	
4. fRepairCostMult
	* Default: 0.90
	* Description: Multiplier used to calculate the cost of repair when paying a smith or other NPC for repairs.
	
5. fRepairSkillBreakBase
	* Default: 30.0
	* Description: Controls base break chance for repair hammers. Is used with fRepairSkillBreakMult to get the final formula.
	* Formula: Not known.
	
6. fRepairSkillBreakMult
	* Default: -0.200
	* Description: Controls base break chance for repair hammers. Is used with fRepairSkillBreakBase to get the final formula. This setting decreases the break chance, so should always be a zero or negative number unless you want hammers to break more often than at 0 skill.
	* Formula: Not known.
	
7. iArmorDamageBootsChance
	* Default: 10
	* Description: Determine the percentage of damage that will be absorbed by a piece of armor. Note: Values should sum to 100 otherwise damage will be "lost"
	
8. iArmorDamageCuirassChance
	* Default: 25
	* Description: Determine the percentage of damage that will be absorbed by a piece of armor. Note: Values should sum to 100 otherwise damage will be "lost"
	
9. iArmorDamageGauntletsChance
	* Default: 10
	* Description: Determine the percentage of damage that will be absorbed by a piece of armor. Note: Values should sum to 100 otherwise damage will be "lost"
	
10. iArmorDamageGreavesChance
	* Default: 15
	* Description: Determine the percentage of damage that will be absorbed by a piece of armor. Note: Values should sum to 100 otherwise damage will be "lost"
	
11. iArmorDamageHelmChance
	* Default: 10
	* Description: Determine the percentage of damage that will be absorbed by a piece of armor. Note: Values should sum to 100 otherwise damage will be "lost"
	
12. iArmorDamageShieldChance
	* Default: 30
	* Description: Determine the percentage of damage that will be absorbed by a piece of armor. Note: Values should sum to 100 otherwise damage will be "lost"
	

</details>

### Alchemy

<details>
<Summary>Alchemy GameSettings</summary>

1. fPotionMortPestleMult
	* Default: 0.25
	* Description: Multipler used to calculate the Magnitude of Player made potions.

2. fPotionT1MagMult
	* Default: 2.5
	* Description: Multiplier used to calculate the Magnitude and Duration of any type 1 effects on all player made potions. Type 1 effects are those with both magnitude and duration (e.g. Damage Magicka). With other default game settings, increasing it will increase the strength and decrease the duration of the effect, and decreasing it will decrease the strength and increase duration.

3. fPotionGoldValueMult
	* Default: 0.45
	* Description: Multiplier used to caluclate the amount of gold Player made potions are worth. 

4. fPotionT1AleDurMult
	* Default: -0.0200
	* Description: Multiplier used to calculate the Duration of hostile type 1 effects on player made potions made with an Alembic. Type 1 effects are those with both magnitude and duration (e.g. Damage Magicka). Increasing it will decrease the strength of the effect, and decreasing it will increase the strength.

5. fPotionT1AleMagMult
	* Default: -0.0200
	* Description: Multiplier used to calculate the Duration of hostile type 1 effects on player made potions made with an Alembic. Type 1 effects are those with both magnitude and duration (e.g. Damage Magicka). Increasing it will decrease the strength of the effect, and decreasing it will increase the strength.

6. fPotionT1CalDurMult
	* Default: 0.0100
	* Description: This Setting has no effect on potion strength.

7. fPotionT1CalMagMult
	* Default: 0.0035
	* Description: Multiplier used to calculate the Magnitude and Duration of any type 1 effects on player made potions made with a Calcinator. Type 1 effects are those with both magnitude and duration (e.g. Damage Magicka). Increasing it will increase the strength of the potion, and decreasing it will decrease the strength.

8. fPotionT1RetDurMult
	* Default: 0.0100
	* Description: Multiplier used to calculate the Duration of beneficial type 1 effects on player made potions made with a Retort. Type 1 effects are those with both magnitude and duration (e.g. Restore Magicka). Increasing it will increase the strength of the effect, and decreasing it will decrease the strength.

9. fPotionT1RetMagMult
	* Default: 0.0050
	* Description: Multiplier used to calculate the Magnitude of beneficial type 1 effects on player made potions made with a Retort. Type 1 effects are those with both magnitude and duration (e.g. Restore Magicka). Increasing it will increase the strength of the effect, and decreasing it will decrease the strength.

10. fPotionT2AleDurMult
	* Default: -0.0200
	* Description: Multiplier used to calculate the Duration of hostile type 2 effects on player made potions made with an Alembic. Type 2 effects are those with no magnitude (e.g. Silence). Increasing it will decrease the strength of the effect, and decreasing it will increase the strength.

11. fPotionT2CalDurMult
	* Default: 0.0025
	* Description: Multiplier used to calculate the Duration of any type 2 effect on player made potions made with a Calcinator. Type 2 effects are those with no magnitude (e.g. Silence). Increasing it will increase the strength of the potion, and decreasing it will decrease the strength.

12. fPotionT2RetDurMult
	* Default: 0.0100
	* Description: Multiplier used to calculate the Duration of beneficial type 2 effects on player made potions made with a Retort. Type 2 effects are those with no magnitude (e.g. Silence). Increasing it will increase the strength of the effect, and decreasing it will decrease the strength.

13. fPotionT3AleMagMult
	* Default: -0.0200
	* Description: There are no such effects in Vanilla Oblivion. Multiplier used to calculate the Magnitude of hostile type 3 effects on player made potions (but not a poison) made with an Alembic. Type 3 effects are those with no duration. Increasing it will decrease the strength of the effect, and decreasing it will increase the strength.

14. fPotionT3CalMagMult
	* Default: 0.0030
	* Description: Multipler used to calculate the Magnitude of any type 3 effect on player made potions made with a Calcinator. Type 3 effects are those with no duration (e.g. Dispel). Increasing it will increase the strength of the potion, and decreasing it will decrease the strength.

15. fPotionT3RetMagMult
	* Default: 0.0050
	* Description: Multiplier used to calculate the Magnitude of beneficial type 3 effects on player made potions made with a Retort. Type 3 effects are those with no duration (e.g. Dispel). Increasing it will increase the strength of the effect, and decreasing it will decrease the strength.
	
16. iMagicMaxPotionsNovice
	* Default: 4
	* Description: The maximum number of potions a Novice of alchemy may drink at once.
	
17. iMagicMaxPotionsApprentice
	* Default: 4
	* Description: The maximum number of potions a Apprentice of alchemy may drink at once.

18. iMagicMaxPotionsJourneyman
	* Default: 4
	* Default (RE): 6
	* Description: The maximum number of potions a Journeyman of alchemy may drink at once.
	
19. iMagicMaxPotionsExpert
	* Default: 4
	* Default (RE): 6
	* Description: The maximum number of potions a Expert of alchemy may drink at once.
	
20. iMagicMaxPotionsMaster
	* Default: 4
	* Default (RE): 10
	* Description: The maximum number of potions a Master of alchemy may drink at once.
	
</details>

### Wortcraft

<details>
<Summary>Wortcraft GameSettings</summary>

1. fWortAlchMult
	* Default: 1.0
	* Description: When using wortcraft, the player's Alchemy is multiplied by this setting, then divided by 5. (Divisor possibly controlled by another setting?) The wortcraft effect is calculated as a potion created by an alchemist with the resulting skill and no equipment bonuses.
	
2. fWortcraftFatigueMag
	* Default: 5.0
	* Description: When an ingredient with the Food property is eaten, the normal wortcraft calculation is skipped and it instead produces an effect with a duration of 1 second and magnitude equal to this setting. (Don't be confused by the name: most food has the Restore Fatigue effect, but this setting affects all food, and non-food Restore Fatigue ingredients are not affected.) Note: Setting the duration of the ingredient effect to zero appears to double the resulting magnitude. Bread, for example, has its Restore Fatigue effect duration set to 0, unlike the majority of ingredients. It restores 10 fatigue instead of 5.

3. iWortcraftMaxEffectsNovice
	* Default: 1
	* Description: This controls how many alchemy effects one can see at Novice level alchemy.
	
4. iWortcraftMaxEffectsApprentice
	* Default: 2
	* Description: This controls how many alchemy effects one can see at Apprentice level alchemy.
	
5. iWortcraftMaxEffectsJourneyman
	* Default: 3
	* Description: This controls how many alchemy effects one can see at Journeyman level alchemy.
	
6. iWortcraftMaxEffectsExpert
	* Default: 4
	* Description: This controls how many alchemy effects one can see at Expert level alchemy.
	
7. iWortcraftMaxEffectsMaster
	* Default: 5
	* Description: This controls how many alchemy effects one can see at Master level alchemy.
	
</details>

## NPC

<details>
<Summary>NPC GameSettings</Summary>

1. fNPCBaseMagickaMult
	* Default: 1.500
	* Description: Value is multiplied by the NPC's intelligence score to determine the NPC's magicka. NPCs do not have birth signs so this value is higher than for the player to compensate. Setting this value higher makes magic using enemies a lot tougher, since more magicka also means faster magicka regeneration.

2. fNPCAttributeHealthMult
	* Default: 0.500
	* Description: Affects how the health of the NPC is calculated based on level and endurance. Increasing this value gives NPCs more health.

1. fEnemyHealthBarTimer
	* Default: 2.5
	* Description: This is a measure of the amount of time in seconds that the health bar of an enemy displays after the cursor moves away.

2. fEssentialDeathTime
	* Default: 10.0
	* Description: The time that an NPC marked essential will remain unconscious before getting back up.

3. fEssentialHealthPercentReGain
	* Default: 0.30
	* Description: The percent of maximum health an essential NPC will have remaining upon recovery.

4. fMinDistanceUseHorse
	* Default: 10000.00
	* Description: When told to go to a point farther away than this distance, an NPC will use a horse if one is available. Any point closer than this distance, and they will simply walk.

5. fFleeDistanceExterior
	* Default: 2000.00
	* Description: Controls how far away an actor (NPC, creature) will run when it flees. Once the actor reaches this distance it will stop fleeing and, usually, just stand there. If you close the distance the actor will continue to flee to this maximum distance.

6. fFleeDistanceInterior
	* Default: 300.00
	* Description: Controls how far away an actor (NPC, creature) will run when it flees. Once the actor reaches this distance it will stop fleeing and, usually, just stand there. If you close the distance the actor will continue to flee to this maximum distance.

7. fDistanceExteriorReactCombat
	* Default: 600.00
	* Description: The distance at which a hostile actor (NPC, creature) will attack, assuming the actor has detected the player.

8. fDistanceInteriorReactCombat
	* Default: 300.00
	* Description: The distance at which a hostile actor (NPC, creature) will attack, assuming the actor has detected the player.
	
9. fHostileActorExteriorDistance
	* Default: 3000.00
	* Description: The distance in game units at which a hostile actor (NPC, creature) is considered close enough to disable fast traveling, waiting, or sleeping for the player.

10. fHostileActorInteriorDistance
	* Default: 2000.00
	* Description: The distance in game units at which a hostile actor (NPC, creature) is considered close enough to disable fast traveling, waiting, or sleeping for the player.

</details>

### AI

<details>
<Summary>AI GameSettings</Summary>

1. fAITalktoNPCtimer
	* Default: 60.00
	* Description: Time in seconds that an NPC will wait after conversation with a NPC before it will attempt another conversation.
	
2. fAItalktoSameNPCtimer
	* Default: 120.00
	* Description: Time in seconds that a NPC will wait before engaging in a conversation with the last NPC to which it spoke.
	
3. fAIMaxWanderTime
	* Default: 100.000
	* Description: Maximum time an actor walks continuously during a wander package, in seconds. After this time they will go idle for some time (probably governed by another setting). Setting this to 0 will make actors walk continuously, except when engaging in conversations with other NPC.

4. fAIFleeConfBase
	* Default: 30.00
	* Description: The base chance that an opponent will flee in combat. It is modified by the opponent's confidence and health.
	* Formula: fAIFleeConfBase + (Confidence * fAIFleeConfMult) + (unknown health factor * fAIFleeHealthMult)
	
5. fAIFleeConfMult
	* Default: -0.500
	* Description: A multiplier on confidence. Raising it makes NPCs less likely to flee.
	
6. fAIFleeHealthMult
	* Default: 10.00
	* Description: The effect that damage has on the AI's chance to flee. Raising this parameter causes loss of health to have a greater effect on the AI and make them more likely to flee when suffering damage.
	
6. iAIDefaultMeleeAlertAllowed
	* Default: 0
	* Description: Seems to have massive consequences. For instance some triggered events don't work properly because the actors might be called into action to fight, and it also seems to work for animals, not just humans. Set to 1 to increase the chance that attacking an actor will alert their nearby friends
	
7. iAIDefaultPowerAttackBackwardChance
	* Default: 20
	* Description: Chance that an enemy will use the Backward Power Attack. Setting to 100 doesn't seem to make every attack a Backwards Power Attack. For instance, when the enemy runs towards you they will still use a normal attack, and will also occasionally (maybe 1/10) use normal attacks. Most likely, there's a formula used to determine if the enemy will use a normal or power attack, and if it's a power attack this (and the other Power Attack chances) determine which Power Attack is used.
	
8. iAINPCRacePowerChance
	* Default: 5
	* Description: Appears to be the chance an NPC will use their race power in battle. For instance, a Dark Elf will use "Summon Ancestral Guardian" in combat.

</details>

### Ranged Combat

<details>
<Summary>Ranged Combat GameSettings</Summary>

1. fArrowOptimalDistance
	* Default: 1000.0
	* Description: Preferred distance for firing this projectile type.Make sure it's always smaller than fMagicArrowOptimalDistance!	

2. fArrowMaxDistance
	* Default: 2000.00
	* Description: Maximum distance for firing this projectile type. Make sure it's always larger than fMagicArrowOptimalDistance!		

3. fMagicBallOptimalDistance
	* Default: 1000.0
	* Description: Preferred distance for firing this projectile type.Make sure it's always smaller than fMagicBallOptimalDistance!	

4. fMagicBallMaximumDistance
	* Default: 2000.00
	* Description: Maximum distance for firing this projectile type. Make sure it's always larger than fMagicBallOptimalDistance!	

5. fMagicBoltOptimalDistance
	* Default: 1000.0
	* Description: Preferred distance for firing this projectile type. Make sure it's always smaller than fMagicBoltOptimalDistance!	

6. fMagicBoltMaximumDistance
	* Default: 2000.00
	* Description: Maximum distance for firing this projectile type. Make sure it's always larger than fMagicBoltOptimalDistance!

7. fMagicFogOptimalDistance
	* Default: 1000.0
	* Description: Preferred distance for firing this projectile type. Make sure it's always smaller than fMagicFogOptimalDistance!	

8. fMagicFogMaximumDistance
	* Default: 2000.00
	* Description: Maximum distance for firing this projectile type. Make sure it's always larger than fMagicFogOptimalDistance!

9. fMagicSprayOptimalDistance
	* Default: 500.0
	* Description: Preferred distance for firing this projectile type. Make sure it's always smaller than fMagicSprayOptimalDistance!	

10. fMagicSprayMaximumDistance
	* Default: 1000.00
	* Description: Maximum distance for firing this projectile type. Make sure it's always larger than fMagicSprayOptimalDistance!

11. fMagicProjectileBaseSpeed
	* Default: 1000.00
	* Description: This is the base speed that spell projectile (ball form) will travel.

12. fMagicProjectileMaxDistance
	* Default: 10000.00
	* Description: Maximum distance that the spell projectiles will travel if they do not make contact with a surface or object.

</details>

### Blink

<details>
<Summary>Blink (Eyelid) GameSettings</Summary>

1. fBlinkDelayMax
	* Default: 4.000
	* Description: Blinking occurs randomly on all NPC's, as well as the player. The amount of time between each "Blink event" is a random number between the minimum delay setting, and the maximum delay setting. Increasing this setting will mean longer periods between blinks (depending on the Max delay variable above) Also realize that, unlike most animations, this time setting will not be affected by the fGlobalTimeMultiplier in the Oblivion.ini file. 1.5 Seconds minimum is always 1.5 seconds, even if the world is moving in slow motion.
	
2. fBlinkDelayMin
	* Default: 1.500
	* Description: Blinking occurs randomly on all NPC's, as well as the player. The amount of time between each "Blink event" is a random number between the minimum delay setting, and the maximum delay setting. Increasing this setting will mean longer periods between blinks (depending on the Max delay variable above) Also realize that, unlike most animations, this time setting will not be affected by the fGlobalTimeMultiplier in the Oblivion.ini file. 1.5 Seconds minimum is always 1.5 seconds, even if the world is moving in slow motion.
	
3. fBlinkDownTime
	* Default: 0.200
	* Description: This refers to how long in seconds it takes for the character's eyelids to go from up to down, and stay down. The time value is means that the eye will stay closed for about 0.1 seconds, and the speed of the eyelid from up to down will be 0.1 seconds (about half the time each). Increasing this value means that the character will take longer to close their eyelids, and the eyelids will stay down longer as well. How long it takes to complete one blink does not seem to matter to the Min and Max blinking time variables - if it takes 15 seconds to blink once, the timer that determines when the next blink will take place will only start once blinking has commenced.
	
4. fBlinkUpTime
	* Default: 0.1700
	* Description: This setting refers to the amount of time, in seconds, it takes the characters eyelids to go from down to up. Decreasing the setting means that the eyelids snap up rather quickly; increasing it means that the eye opening is a much slower process.

</details>

## Movement

<details>
<Summary>Movement GameSettings</Summary>

1. fMoveCharWalkMin
	* Default: 90.0
	* Description: Minimum base walking speed

2. fMoveCharWalkMax
	* Default: 130.0
	* Description: Maximum base walking speed

3. fMoveCreatureWalkMin
	* Default: 5.0
	* Description: Minimum base walking speed for creatures

4. fMoveCreatureWalkMax
	* Default: 300.0
	* Description: Maximum base walking speed for creatures

5. fMoveEncumEffect
	* Default: 0.4
	* Description: Worn armor/weapons encuberence affect with weapon ready

6. fMoveEncumEffectNoWea
	* Default: 0.3
	* Description: Worn armor/weapons encuberence affect without weapon ready

7. fMoveWeightMin
	* Default: 0.0
	* Description: Movement encumberance minimum worn weight

8. fMoveWeightMax
	* Default: 150.0
	* Description: Movement encumberance maximum worn weight

9. fMoveNoWeaponMult
	* Default: 1.1
	* Description: Speed multiplier without weapon ready

10. fMoveRunMult
	* Default: 3.0
	* Description: Speed multiplier for being in run mode

11. fMoveRunAthleticsMult
	* Default: 1.0
	* Description: Speed multiplier for athletics when in run mode

12. fMoveSneakMult
	* Default: 0.6
	* Description: Speed multiplier for being in sneak mode

13. fPerkHeavyArmorExpertSpeedMult
	* Default: 0.5
	* Description: Perk worn heavy armor weight multiplier??? (Initial value of 0.5 reduces worn armor weight by half)

14. fPerkHeavyArmorMasterSpeedMult
	* Default: 0.0
	* Description: Perk worn heavy armor weight multiplier, replacing above??? (Initial value of 0 reduces worn armor weight to 0)

15. fPerkHeavyArmorSinkGravityMult
	* Default: 15.0
	* Description: Unknown impact perk

16. fPerkLightArmorExpertSpeedMult
	* Default: 0.0
	* Description: Perk worn light armor weight multiplier??? (Initial value of 0 reduces worn armor weight to 0)

17. fArmorWeightLightMaxMod
	* Default: 0.6
	* Description: Unknown impact setting

18. fMoveSwimWalkBase
	* Default: 0.5
	* Description: Unknown impact setting

19. fMoveSwimWalkAthleticsMult
	* Default: 0.02
	* Description: Unknown impact setting

20. fMoveSwimRunBase
	* Default: 0.5
	* Description: Unknown impact setting

21. fMoveSwimRunAthleticsMult
	* Default: 0.1
	* Description: Unknown impact setting

22. fSubmergedMaxSpeed
	* Default: 2.0
	* Description: Unknown impact setting

23. fMoveMinFlySpeed
	* Default: 5.0
	* Description: Minimum flying speed

24. fMoveMaxFlySpeed
	* Default: 300.0
	* Description: Maximum flying speed

</details>

### Falling

<details>
<Summary>Falling GameSettings</Summary>

1. fJumpFallSkillBase
	* Default: 1.2500
	* Description: Final falling damage is determined based on several factors, most notably fJumpFallTimeMult.
	* Formula: base damage * (fJumpFallSkillBase - (Acrobatics * fJumpFallSkillMult / 100))

2. fJumpFallSkillMult
	* Default: -0.0100
	* Description: Final falling damage is determined based on several factors, most notably fJumpFallTimeMult.
	* Formula: base damage * (fJumpFallSkillBase - (Acrobatics * fJumpFallSkillMult / 100))

3. fJumpFallTimeBase
	* Default: 0.000
	* Description: Appears to be the minimum amount of damage taken in a fall, regardless of time spent falling. Note that a certain threshold of vertical distance has to be passed before it's considered a fall. Further experimentation may reveal other GMSTs which control this.
	
4. fJumpFallTimeMin
	* Default: 0.2000
	* Description: Falling damage is calculated by time in seconds spent falling; see fJumpFallTimeMult. This setting appears to be the minimum time spent falling before damage is assigned at all. However, setting it to 0.0 does not cause you to take damage by stepping off a curb, so there must be an additional factor in determining whether or not you've fallen.
	
5. fJumpFallTimeMult
	* Default: 80.0000
	* Description: The base amount of damage taken per second of falling. This is adjusted by fJumpFallSkillBase and fJumpFallSkillMult.
	
6. fJumpFallVelocityMin
	* Default: 600.0000
	* Description: This seems to influence how quickly actors fall through the air.
	
7. fJumpHeightMax
	* Default: 164.0000
	* Description: This number sets the height of a jump made by a character with an Acrobatics skill of 100. This number must be higher than fJumpHeightMin (default 64.0000).
	* Formula: fJumpHeightMin + (Acrobatics * (fJumpHeightMax - fJumpHeightMin) / 100)
	
8. fJumpHeightMin
	* Default: 64.0000
	* Description: This number sets absolute minimum for any jump the player under any circumstances, including the case when Acrobatics skill is 0. This number must be lower than fJumpHeightMax (default 164.0000).
	
9. fJumpMoveBase
	* Default: 0.000
	* Description: This is the base value of how much control you have over moving/controlling the direction of your character while in the air. The final value is also affected by fJumpMoveMult.
	
10. fJumpMoveMult
	* Default: 0.3000
	* Description: This number is a multiplier or 'weight' that affects the fJumpMoveBase value to determine how much 'in-flight' directional control you have over your character.

</details>

## Physics

<details>
<summary>Physics GameSettings</summary>

1. fObjectHitWeaponReach
	* Default: 150.000
	* Description: Dictates how far ALL weapons reach to hit any object such as a tree. Unlike hitting actors, Weapon Range will not effect how far you can reach with your weapon to hit objects.
	
2. fGrabPower
	* Default: 2.000
	* Description: Controls the amount of power the player has when manipulating objects with the Grab key (default: Z). Increasing this number increases the rate at which an object can be moved using the grab key.
	
</details>

### Arrows

<details>
<summary>Arrows GameSettings</summary>

1. fArrowAgeMax
	* Default: 90.000
	* Description: The number of seconds an arrow remains on the ground, or stuck into a world object, after impact. This setting does not apply to arrows striking an actor, these arrows remain in the actor's inventory until removed (sold, used, stolen, removed by script, etc). Recovery chance is determined by IArrowInventoryChance.

2. fArrowBounceLinearSpeed
	* Default: 0.100
	* Description: This controls the speed at which arrows bounce back (i.e., if you set this to 1.0000, and shoot an arrow at a stone wall, the arrow will bounce back at you at the same speed it was fired). Setting this to 0.5000 will set it to bounce back at 1/2 speed. Setting it to 0 will (in theory) stop it from bouncing back.

3. fArrowBounceRotateSpeed
	* Default: 7.500
	* Description: This setting controls how much the arrow rotates after it bounces off of something (i.e., if you set this to 0.0500, the arrow will not rotate very much after bouncing off something).

4. fArrowFakeMass
	* Default: 0.2500
	* Description: How "heavy" an arrow is considered to be for purposes of calculating havoc functions. Probably used mostly when arrows impact havoc objects.

5. fArrowFOVTimeChange
	* Default: 0.250
	* Description: it is an increment (or decrement) of some sort that affects zoom speed.

6. fArrowFOVTimeStart
	* Default: 2.750
	* Description: It is believed to be the base value for zooming speed. See fArrowFOVTimeChange to determine how zooming can be speed up.

7. fArrowFOVZoom
	* Default: 30.000
	* Description: This is the FOV setting towards which the current FOV is adjusted (and where it stops). See fArrowFOVTimeStart and fArrowFOVTimeChange to determine the speed of zoom effect.

8. fArrowGravityBase
	* Default: 0.300
	* Description: Believed to be the base force pulling the arrow towards the ground - for arc calculation. The smaller the value, the staighter the arrow's arc.

9. fArrowGravityMin
	* Default: 0.0500
	* Description: Changing this setting did not appear to do anything to arrows. While keeping the gravity multiplier at the same setting, going from a GravityMin value of 0.001 to 90,000 did nothing to change the arc of the arrow.

10. fArrowGravityMult
	* Default: 0.0020
	* Description: This multiplier determines the gravity on arrows. If you increase this amount, arrows will fly straight for a longer period of time. If you decrease the amount, arrows will go straight for a much shorter period of time.

11. fArrowSpeedMult
	* Default: 1500.000
	* Description: The base speed at which fired arrows fly in units/sec.
	* Formula: (Speed prop. of Arrow) * fArrowSpeedMult * (fArrowWeakSpeed + (1 - fArrowWeakSpeed)*DrawMult
	* DrawMult = fArrowBowTimerBase + fArrowBowTimerMult * DrawTime  ,  or 1.0 (whichever is less)
	
12. fArrowBowTimerBase
	* Default: 0.2500
	* Description: The speed of arrows that haven't been drawn back all of the way.

13. fArrowBowTimerMult
	* Default: 0.400
	* Description: Determines the rate at which the arrow is drawn back while the fire button is held. 

14. fArrowWeakGravity
	* Default: 1.750
	* Description: This setting determines the gravity effect on arrows that haven't been held back for the proper length of time (not a power shot). Decreasing this setting means that your "weak" arrows will have a straighter arc than normal (travel in a straight line for a longer period of time).

15. fArrowWeakSpeed
	* Default: 0.0100
	* Description: Determines the minimum speed, as a fraction of the base speed, for arrows that aren't drawn back all of the way. See the full speed formula for details.

16. iArrowInventoryChance
	* Default: 50
	* Description: The percent chance that an arrow that struck its target will be added to the target's inventory.
	
17. iArrowMaxRefCount
	* Default: 15
	* Description: The maximum number of Arrow References that are kept track of in a cell caused by rebounding arrows.

</details>

### Death Force

<details>
<summary>Death Force GameSettings</summary>

1. fDeathForceForceMin
	* Default: 35.0
	* Description: This, along with fDeathForceForceMax, determines how much force is allowed when someone dies.

2. fDeathForceForceMax
	* Default: 85.0
	* Description: This, along with fDeathForceForceMin, determines how much force is allowed when someone dies.

</details>

### Explosion Force

<details>
<summary>Explosion Force GameSettings</summary>

1. fMagicExplosionPowerMax
	* Default: 100.00
	* Description: This value has to do with the maximum "kick" an explosion of magic uses. This is how far an actor of any type will be moved by magic. This seems to only affect actors that are dead or paralyzed. This also seems to affect movable in-game items, however they accelerate at a much greater distance and speed, so weight must be a factor too. This value is used as a maximum upper end if the game calculates a higher value. (My value is 128.000 which seems to be more than sufficient.)

2. fMagicExplosionPowerMin
	* Default: 0.0
	* Description: Like fMagicExplosionPowerMax, this value seems to deal with the minimum force applied to an actor with magic. The game will use this absolute minimum if a calculated value falls below this range.

3. fMagicExplosionPowerMult
	* Default: 0.40
	* Description: This setting is likely part of a formula the game uses to determine what "kick" a magic bolt or explosion has. The formula appears to be based on: The damage the spell does, the area of the spell, this value, and the weight of the object. This only seems to work when the target is paralyzed, dead, or a moveable object.

</details>

### Buoyancy

<details>
<summary>Buoyancy GameSettings</summary>

* All of the fBuoyancy settings control the buoyancy (how fast or slow an object will sink when dropped in a pool of water) of some type of material in the game. A setting of -1.000 means the material will sink immediately to the bottom of the water. A setting of 0.000 means the material will slowly settle into a mid-level height in the water. A setting of +1.000 means the material will float on top of the water. Other values control the speed at which the material will sink and the height at which it floats

1. fBuoyancyCloth
	* Default: 0.75
	* Description: Buoyancy value for materials of the Cloth category.
	
2. fBuoyancyDirt
	* Default: 0.25
	* Description: Buoyancy value for materials of the Dirt category.
	
3. fBuoyancyGlass
	* Default: -0.200
	* Description: Buoyancy value for materials of the Glass category.
	
4. fBuoyancyGrass
	* Default: 0.25
	* Description: Buoyancy value for materials of the Grass category.
	
5. fBuoyancyMetal
	* Default: -1.00
	* Description: Buoyancy value for materials of the Metal category.
	
6. fBuoyancyMultBody
	* Default: 1.00
	* Description: The fBuoyancyMultBody setting is the multiplier that applies to the main body of the object.
	
7. fBuoyancyMultExtremity
	* Default: -0.3000
	* Description: The fBuoyancyMultExtremity is a multiplier for the fBuoyancy setting of a given material. Multiplying the MultExtremity value by the "Material" value will produce the final buoyancy of the object. 
	
8. fBuoyancyOrganic
	* Default: 0.75
	* Description: Buoyancy value for materials of the Organic category.
	
9. fBuoyancySkin
	* Default: 0.75
	* Description: Buoyancy value for materials of the skin category.
	
10. fBuoyancyStone
	* Default: -0.75
	* Description: Buoyancy value for materials of the stone category. Rocks, granite, slate, pebbles, and such.
	
11. fBuoyancyWater
	* Default: 0.00
	* Description: fBuoyancyWater is like a reference value. It sets the buoyancy of water. Setting it to 1.0000 makes everything sink. Setting it to -1.0000 makes everything float and could possibly induce a permanent "water-walk" effect for all characters.

12. fBuoyancyWood
	* Default: 1.00
	* Description:  Buoyancy value for materials of the wood category. These include chairs, desks, barrels, and other furniture. Also, driftwood and any items you find that are made of wood.

</details>

## Camera

### Vanity

<details>
<summary>Vanity GameSettings</summary>

1. fVanityModeWheelMult
	* Default: 0.1000
	* Description: This value changes the multiplier that determines the speed your camera zooms in and out of Vanity Mode (or 3rd person). Increasing or decreasing the value will increase or decrease the distance traveled by one click of the scroll wheel.
	
2. fVanityModeWheelMax
	* Default: 600.0
	* Description: This is the maximum distance from the camera to the center of the player while in Vanity Mode. Distance is based on the Coordinate in the game, same on all 3 axis. Increasing the number should allow you to have the camera further than normal.
	
3. fVanityModeWheelMin
	* Default: 30.00
	* Description: This is the minimum distance from the player the camera can be set when you are in Vanity Mode. Distance is the value according to the coordinate system in the game, on all 3 Axis. Since the height of the player is more than 30, the minimum Z distance clips through the player.
	
4. fVanityModeXMult
	* Default: 30.00
	* Description: Refers to the multiplier that controls of the speed you move the camera on the X axis (The speed that the camera spins around your character while in Vanity Mode, not the same as the X axis for the Coordinate system on the map). Increasing or decreasing the multiplier will increase or decrease the distance traveled by the camera as it spins around your character.
	
5. fVanityModeYMult
	* Default: 10.00
	* Description: This setting controls the multiplier for the Y axis (Y axis meaning going up and over your character, not the same Y axis as the coordinate system on the map). Increasing or decreasing this number will increase or decrease the distance traveled by the camera while in Vanity Mode.
	
6. fVanityModeDelay
	* Default: 0.50
	* Description: This setting changes the delay period between going from 3rd person to Vanity Mode. In particular, it determines how long you hold down "R" before you make the switch. If you set it to zero, when you are in first person mode, and you press R, you will go straight to Vanity Mode, instead of 3rd person. You can still go into third person mode via the scroll wheel, but you can't use "R" for 3rd person mode once this has been set to zero.
	
7. fChase3rdPersonZUnitsPerSecond
	* Default: 300.000
	* Description: Distance in units per second the third person chase camera zooms back to its set value. If the value of the Game Setting fVanityModeWheelMax is increased, increasing the value of this variable proportionately helps reach the desired zoom distance quickly.

</details>

## Miscellaneous

<details>
<summary>Miscellaneous GameSettings</summary>

1. iInventoryAskQuantityAt
	* Default: 3
	* Description: Setting that determines when to show the amount slider for selecting multiple items when items are selected in the inventory menu.

2. iMaxArrowsInQuiver
	* Default: 20
	* Description: This is the maximum amount of arrows that can be rendered in a quiver on the back of an actor. Increasing this beyond 20 would probably cause clipping or crowding issues.

</details>

### Stars

<details>
<summary>Stars GameSettings</summary>

1. fStarsRotateDays
	* Default: 4.0
	* Description: This setting dictates how often the stars rotate in the sky. In particular, this setting is in days. If you set this to a very small setting, the stars will rotate far faster than normal. The speed of their rotation is determined using the other 3 variables, each dictating the number of rotations per period (for each axis). If you set RotateDays to 0.0004, and each of the Axis to 1, then, all 3 axis will make one full rotation every second (roughly).
	* If all three rotation variables are set to zero, then the stars will fade in and out based on this setting.

2. fStarsRotateXAxis
	* Default: 0.0
	* Description: Determines how many rotations are made on the X axis per period (period is defined by FStarsRotateDays). The X axis will move around you like you are in a barrel (A curved pattern, going from right to left across the screen).
	
3. fStarsRotateYAxis
	* Default: 0.0
	* Description: Determines how many rotations are made on the Y axis per period (period is defined by FStarsRotateDays). The Y axis will move around you like you are in a barrel (A curved pattern, going from right to left across the screen, depending on where you are facing).
	
4. fStarsRotateZAxis
	* Default: 1.0
	* Description: Determines how many rotations are made on the X axis per period (period is defined by FStarsRotateDays). The Z axis will spin around above you, counterclockwise.
	
</details>


## Unknown Unused and Broken

<details>
<summary>Obsolete GameSettings</summary>

1. fDifficultyDamageMultiplier (As of ObRe 1.2, this setting is obsolete, and has been replaced by 12 individual settings for each difficulty setting) 
	* Default: 5.00
	* Description: Difficulty affects how much damage the player does in combat, and how much damage they receive. Damage of all types is affected by Difficulty. 
	* This multiplier is the maximum amount the damage the player can do when difficulty is set to Novice. It divides the amount of damage done to the player by the same value. 
	* Difficulty GameSettings can be made more subtle by lowering this value, and more extreme by raising it.
	* (Player will receive 1/5th normal damage and deal 5x normal damage on Novice) 
	* (Player will receive 1/3.5th normal damage and deal 3.5x normal damage on Apprentice)
	* (Player will receive 1x normal damage and deal 1x normal damage on Adept)
	* (Player will receive 3.5x normal damage and deal 1/3.5th normal damage on Apprentice)
	* (Player will receive 5x normal damage and deal 1/5th normal damage on Master.) 

2. fDifficultyDefaultValue
	* Default: 0.0
	* Description: The default difficulty value.

3. fDifficultyMaxValue
	* Default: 1.0
	* Description: The maximum difficulty value.

4. fDifficultyMinValue
	* Default: -1.0
	* Description: The minimum difficulty value.

5. fAutoDoorActivateDistance
	* Default: 150.000
	* Description: The distance from a gate or a door from which you can activate it. 

6. iActivatePickLength
	* Default: 150
	* Description: The distance at which the player can activate objects in the game world. This covers everything from talking to NPCs, searching containers, pickpocketing, using doors, etc.

</details>

<details>
<summary>Unused GameSettings</summary>

1. fDemandMult
2. fDemandBase

3. fBribeMult
	* Default: 0.3000
	* Description: Unused setting. Multiplier times the combined levels and skills of the two actors.

4. fBribeBase
	* Default: 2.0000
	* Description: Unused setting. Sets the lowest bribe value and is used as an offset.
	
5. fBlockScoreNoShieldMult
	* Default: 0.5
	* Description: Limits the effectiveness of your block skill when you are blocking with a weapon or hand-to-hand. In crude terms, a value of 0.5 means that your block skill is halved when you block with a weapon or hand-to-hand. A value of 1.0 means that blocking with a weapon or hand-to-hand uses the same effective block skill as when you use a shield. The actual formula is more complicated than that and is not fully known. This setting also affects blocking by NPCs and creatures. However, testing suggests that this setting has no actual effect. It is likely a setting that was deprecated when it was replaced by FBlockAmountWeaponMult and FBlockAmountWeaponMult.
	
6. fBarterDispositionMod
	* Default: 0
	* Description: This setting is not used by the barter system.
	
7. fAIRadiusToRunDetectionExterior
	* Default: 0
	* Description: No longer used. This setting was replaced by fSneakMaxDistance
	
8. fAIRadiusToRunDetectionInterior
	* Default: 0
	* Description: No longer used. This setting was replaced by fSneakMaxDistance

2. iLevelUpXXMult
	* Default: 2
	* Description: Attribute increases are no longer determined by the specific skills the player has raised. Instead, a new system has been implemented:

1. fMagicFatigueDrainBase
	* Default: 1.0
	* Description: Used with fMagicFatigueDrainMult to determine the effect of fatigue on spell effectiveness. By default, fatigue has no effect on spellcasting.
	* Formula: spell effectiveness penalty = 1 - fMagicFatigueDrainBase - fMagicFatigueDrainMult x (fatigue / maximum fatigue)

2. fMagicFatigueDrainMult
	* Default: 0.0
	* Description: Used with fMagicFatigueDrainBase to determine the effect of fatigue on spell effectiveness. By default, fatigue has no effect on spellcasting.
	* Formula: spell effectiveness penalty = 1 - fMagicFatigueDrainBase - fMagicFatigueDrainMult x (fatigue / maximum fatigue)


</details>

<details>
<summary>Unknown GameSettings</summary>

* These Settings do not have descriptions yet.

**Unkown Absorb GameSettings**
fAbsorbBoltGrowWidth
fAbsorbBoltSmallWidth
fAbsorbBoltsRadius
fAbsorbBoltsRadiusStrength
fAbsorbCoreColorB
fAbsorbCoreColorG
fAbsorbCoreColorR
fAbsorbGlowColorB
fAbsorbGlowColorG
fAbsorbGlowColorR
fAbsorbMoveSpeed
fAbsorbSegmentLength
fAbsorbSegmentVariance
fAbsorbTortuosityVariance

**Unkown Actor GameSettings**
fActorTurnAnimMinTime
fActorWeaponDesirabilityDamageMult
fActorWeaponDesirabilitySkillMult
fActorArmorDesirabilityDamageMult
fActorArmorDesirabilitySkillMult

**Unknown AI GameSettings**
fAIAcquireObjectDistance
fAIAquireKillBase
fAIAquireKillMult
fAIAquirePickBase
fAIAquirePickMult
fAIAquireStealBase
fAIAquireStealMult
fAIAwareofPlayerTimer
fAIBestHeadTrackDistance
fAICombatFleeScoreThreshold
fAICombatNoAreaEffectAllyDistance
fAICombatNoTargetLOSPriorityMult
fAICombatSlopeDifference
fAICombatTargetUnreachablePriorityMult
fAICombatUnreachableTargetPriorityMult
fAIConversationExploreTime
fAIDefaultAttackDuringAttackMult
fAIDefaultAttackDuringBlockMult
fAIDefaultAttackDuringRecoilStaggerBonus
fAIDefaultAttackDuringUnconsciousBonus
fAIDefaultAttackHandBonus
fAIDefaultAttackNoAttackMult
fAIDefaultAttackSkillBase
fAIDefaultAttackSkillMult
fAIDefaultBlockDuringAttackMult
fAIDefaultBlockNoAttackMult
fAIDefaultBlockSkillBase
fAIDefaultBlockSkillMult
fAIDefaultBuffStandoffDistance
fAIDefaultDodgeBackDuringAttackMult
fAIDefaultDodgeBackNoAttackMult
fAIDefaultDodgeBackwardMaxTime
fAIDefaultDodgeBackwardMinTime
fAIDefaultDodgeDuringAttackMult
fAIDefaultDodgeFatigueBase
fAIDefaultDodgeFatigueMult
fAIDefaultDodgeFowardMaxTime
fAIDefaultDodgeFowardMinTime
fAIDefaultDodgeForwardNotAttackingMult
fAIDefaultDodgeForwardWhileAttackingMult
fAIDefaultDodgeLeftRightMaxTime
fAIDefaultDodgeLeftRightMinTime
fAIDefaultDodgeNoAttackMult
fAIDefaultDodgeSpeedBase
fAIDefaultDodgeSpeedMult
fAIDefaultGroupStandoffDistance
fAIDefaultHoldMaxTime
fAIDefaultHoldMinTime
fAIDefaultIdleMaxTime
fAIDefaultIdleMinTime
fAIDefaultMaximumRangeMult
fAIDefaultOptimalRangeMult
fAIDefaultPowerAttackFatigueBase
fAIDefaultPowerAttackFatigueMult
fAIDefaultPowerAttackRecoilStaggerBonus
fAIDefaultPowerAttackUnconsciousBonus
fAIDefaultRangedStandoffDistance
fAIDefaultRushingAttackDistanceMult
fAIDefaultSwitchToMeleeDistance
fAIDefaultSwitchToRangedDistance
fAIDodgeDecisionBase
fAIDodgeFavorLeftRightMult
fAIDodgeVerticalRangedAttackMult
fAIDodgeWalkChance
fAIEnergyLevelBase
fAIEngergyLevelMult (sic)
fAIEscortWaitDistanceExterior
fAIEscortWaitDistanceInterior
fAIExteriorSpectatorDetection
fAIExteriorSpectatorDistance
fAIFaceTargetAnimationAngle
fAIFleeSuccessTimeout
fAIGreetingTimer
fAIIdleAnimationDistance
fAIIdleWaitTime
fAIInteriorHeadTrackMult
fAIInteriorSpectatorDetection
fAIInteriorSpectatorDistance
fAIMagicSpellMult
fAIMagicTimer
fAIMaxHeadTrackDistance
fAIMaxHeadTrackDistanceFromPC
fAIMaxSmileDistance
fAIMeleeArmorMult
fAIMeleeHandMult
fAIMeleeWeaponMult
fAIMinGreetingDistance
fAIMoveDistanceToRecalcFollowPath
fAINPCSpeechMult
fAIPowerAttackCreatureChance
fAIPowerAttackFatigueBase
fAIPowerAttackFatigueMult
fAIPowerAttackKnockdownBonus
fAIPowerAttackNPCChance
fAIPowerAttackRecoilBonus
fAIPursueDistanceLineOfSight
fAIRadiusToRunDetectionExterior
fAIRadiusToRunDetectionInterior
fAIRangedWeaponMult
fAIRangMagicSpellMult (sic)
fAISocialchanceForConversation
fAISocialchanceForConversationInterior
fAISocialRadiusToTriggerConversation
fAISocialRadiusToTriggerConversationInterior
fAISpectatorCommentTimer
fAITrespassWarningTimer
fAIUpdateMovementRestrictionsDistance
fAIYieldBase
fAIYieldDurationBase
fAIYieldDurationMult
fAIYieldMult
fAlchemyGoldMult

**Unknown Enchantment GameSettings**

3. fEnchantmentEffectPointsMult
	* Default: 0.40
	* Description: ?

4. fMagicEnchantmentChargeBase
	* Default: 0.0
	* Description:  ?

5. fMagicEnchantmentChargeMult
	* Default: 1.0
	* Description: ?

6. fMagicEnchantmentDrainBase
	* Default: 0.0
	* Description: ?

7. fMagicEnchantmentDrainMult
	* Default: 0.25
	* Description: ?

8. fMagicDefaultCEEnchantFactor
	* Default: 1.0
	* Description: ?

9. fMagicDefaultCEBarterFactor
	* Default: 1.0
	* Description: ?

**Unknown Sun Damage GameSettings**

1. fMagicSunDamageBaseDamage
2. fMagicSunDamageMinWeather
3. fMagicSunDamagePainInitialDelay
4. fMagicSunDamagePainTimer
5. fMagicSunDamageScreenGlowMult
6. fMagicSunDamageScreenGlowRateDown
7. fMagicSunDamageScreenGlowRateUp

**Unknown Knockdown GameSettings**

1. fKnockdownAgilBase
2. fKnockdownAgilMult
3. fKnockdownDamageBase
4. fKnockdownDamageMult

**Unknown Vanity GameSettings**

1. fVanityModeAutoDelay
	* Default: 120.0
	* Description: ?
	
2. fVanityModeAutoXSpeed
3. fVanityModeAutoYDegrees
4. fVanityModeAutoYSpeed
5. fVanityModeForceDefault
6. fVanityModeWheelDeadMin
7. fVanityModeWheelDefault

</details>

<details>
<summary>Broken GameSettings</summary>

1. fDefaultNoticeTextDisplayTime
	* Description: Presumably should set the default time for which a message is displayed on screen, but apparently does not work. This at least is consistent with DisplaySeconds argument for message, which also does not work.
	
2. fAIDefaultSpeechMult
	* Default: 0.050
	* Description: This setting does not work, and appears to conflict with normal NPC dialogue. Do not use it.

</details>