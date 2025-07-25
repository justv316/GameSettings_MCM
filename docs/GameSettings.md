# Game Settings

	* [Comprehensive Settings List](https://cs.uesp.net/wiki/Comprehensive_Settings_List)

# Table of Contents

1. [Gameplay Settings](#Gameplay)
	* [Difficulty Settings](#Difficulty)
	* [Skill Settings](#Skills)
2. [Damage Settings](#Damage)

## Gameplay

<details>
<Summary>Gameplay Settings</Summary>

### Difficulty
	
1. fDifficultyDamageMultiplier
	* Default: 5.00
	* Description: Difficulty affects how much damage the player does in combat, and how much damage they receive. Damage of all types is affected by Difficulty. 
	* This multiplier is the maximum amount the damage the player can do when difficulty is set to Novice. It divides the amount of damage done to the player by the same value. 
	* Difficulty Settings can be made more subtle by lowering this value, and more extreme by raising it.
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


### Skills

fSkillUseMinorMult
	* Default (RE): 0.875

</details>

## Damage

<details>
<Summary>Damage Game Settings</summary>

### Damage Formula

[Complete Damage Formula](https://en.uesp.net/wiki/Oblivion:The_Complete_Damage_Formula#Modifiable_Settings)

1. fDamageSkillBase
	* Default: 0.20
	* Description: This value is used in the formula that determines the actual damage done by a weapon. This multiplier is used to determine the damage a weapon will do if the actor has a skill of zero. There are other factors that determine the actual damage done, such as strength, fatigue and fDamageSkillMult.

2. fDamageSkillMult
	* Default: 1.50
	* Description: This value is multiplied times the actor's skill as part of the calculation used to determine how much damage a weapon does in combat. Actors with a skill of 100 would get the full multiplier and actually do more damage than the weapon is rated for by default. Other factors in determining damage done by weapons are strength, fatigue and fDamageSkillBase.

3. fDamageStrengthBase
	* Default: 0.75
	* Description: Used to calculate the damage-multiplier received from attributes. 
	* For BLUNT and BLADE weapons the actor's current Strength is used
	* For MARKSMAN the actor's current agility is used. 
	* Both are capped at 100, meaning that fortifying your strength over 100 won't result in more damage.
	* Formula: fDamageStrengthBase + Attribute/100 x fDamageStrengthMult

4. fDamageStrengthMult
	* Default: 0.50
	* Description: Used to calculate the damage-multiplier received from attributes.
	* For BLUNT and BLADE weapons the actor's current Strength is used
	* For MARKSMAN the actor's current agility is used. 
	* Both are capped at 100, meaning that fortifying your strength over 100 won't result in more damage.
	* Formula: fDamageStrengthBase + Attribute/100 x fDamageStrengthMult

5. fDamageToArmorPercentage
	* Default: 9.0
	* Description: Determines how much damage armor receives when used in combat. Might also affect how much damage it receives from the damage armor spell, needs to be tested.

6. fDamageToWeaponPercentage
	* Default: 0.06
	* Description: Determines how much damage a weapon receives when used in combat.

7. fDamageWeaponConditionBase
	* Default: 0.50
	* Description: 
	* Description: Together with fDamageWeaponConditionMult this determines the amount of damage your weapon does based on it's current health.
*Example:  Setting this value to 1 and fDamageWeaponConditionMult to 0 means that weapons will always deal the same amount of damage, regardless of health, up to the point of breaking.

8. fDamageWeaponConditionMult
	* Default: 0.50
	* Description: Together with fDamageWeaponConditionBase this determines the amount of damage your weapon does based on it's current health.
	* Example: Setting this value to 0 and fDamageWeaponConditionBase to 1 means that weapons will always deal the same amount of damage, regardless of health, up to the point of breaking.

9. fDamageWeaponMult
	* Default: 0.50
	* Description: Adjusting this value, alters all weapon damage proportionately.
	* This variable has no effect on spell damage.
	* Example: a value of 1.5 will triple the damage of all weapons, in the game. A sword with 10 damage, will become a 30 damage sword. The altered value will display correctly in the game text.

### Power attack

1. fPowerAttackDelay
	* Default: 0.3000
	* Description: The amount of time the attack button must be held before a power attack will be executed, and also affects how long a power attack takes. 


### Power Attack Maneuvers

1. fDamagePowerAttackBackBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

2. fDamagePowerAttackForwardBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

3. fDamagePowerAttackSideBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

4. fDamagePowerAttackStandBonus
	* Default: 3.00
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

5. fDamagePowerAttackBonus
	* Default: 2.50
	* Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

</details>

### Armor

<details>
<Summary>Armor Game Settings</summary>


1. fMaxArmorRating
	* Default: 85.0
	* Description: Determines the maximum amount of armor. This decimal value is used to determine the maximum armor contribution of all equipped items and effects. The default is 85.00. Since armor rating is the percentage of damage withheld from the target, the best that any combination of armor can do is remove 85% of damage done. It would be potentially dangerous to let this value get too close to 100.

	* Fractional values are retained at all times. An actor's health is a floating point value, as are the weapon damage and armor rating. All calculations are made as floats. Every piece of armor contributes it's armor value directly to this value. Every % of shield and fire/shock/frost shield also adds 1 armor. A value of 0 removes the cap entirely (no limit to armor rating).

</details>

## Stealth

<details>
<Summary>Stealth Game Settings</summary>

### Sneak Damage

1. fDamageSneakAttackMult
	* Default: 4.0
	* Description: Multiplies the base attack by this value before applying the damage to an enemy. It is activated when a player initiates an attack while in sneak mode, thus the "Sneak Attack x#" message when you perform a sneak attack on an enemy. This value is a base value for sneak attacks and is further modified by a character's sneak skill, weapon type (melee or ranged), attack direction (front, back, side, sleep), and attack type (normal or power). Each of these modifiers has its own setting.

### Sneak Mechanics

1. fDetectionTimerSetting
	* Default: 0.300
	* Description: This value represents how often in seconds an actor makes detection checks against all other actors within the max detection distance.

2. fDetectionSneakLightMod
	* Default: -5.000
	* Description: This value is added to the light level on a target during Detection calculations.

3. fDetectionNightEyeBonus
	* Default: 3.000
	* Description: Bonus multiplier to the light level on nearby actors during detection checks.

</details>

## Magic

<details>
<Summary>Magic Game Settings</summary>

### Magicka Cost

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

### Magicka Regeneration

1. fMagickaReturnBase
	* Default: 0.75
	* Description: Base value for magicka regeneration rate.
	* Formula: MagickaRegenRate = 0.01 	* (fMagickaReturnBase + fMagickaReturnMult 	* Willpower) 	* TotalMagicka

2. fMagickaReturnMult
	* Default: 0.020
	* Description: Multiplier used to calculate magicka regeneration rate.
	* Formula: MagickaRegenRate = 0.01 	* (fMagickaReturnBase + fMagickaReturnMult 	* Willpower) 	* TotalMagicka

### Enchantment

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

### Soulgems

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


### Alchemy

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

iMagicMaxPotionsJourneyman
	* Default (RE): 6

iMagicMaxPotionsExpert
	* Default (RE): 6

iMagicMaxPotionsMaster
	* Default (RE): 10



### Magic Etc.

#### Spell level

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

#### Disease

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


#### Magic Lights

1. fMagicLightForwardOffset
	* Default: 22.0
	* Description: When casting a light spell, this is the distance in front of the player that the center of the light will be placed.

2. fMagicLightHeightOffset
	* Default: -96.0
	* Description: When casting a light spell, this is the height distance above the player that the center of the light will be placed.

3. fMagicNightEyeAmbient
	* Default: 0.75
	* Description: Affects Magic Night-Eye brightness. Higher value means brighter view.

#### Uncategorized

1. fMagicFatigueDrainBase
	* Default: 1.0
	* Description: Used with fMagicFatigueDrainMult to determine the effect of fatigue on spell effectiveness. By default, fatigue has no effect on spellcasting.
	* Formula: spell effectiveness penalty = 1 - fMagicFatigueDrainBase - fMagicFatigueDrainMult x (fatigue / maximum fatigue)

2. fMagicFatigueDrainMult
	* Default: 0.0
	* Description: Used with fMagicFatigueDrainBase to determine the effect of fatigue on spell effectiveness. By default, fatigue has no effect on spellcasting.
	* Formula: spell effectiveness penalty = 1 - fMagicFatigueDrainBase - fMagicFatigueDrainMult x (fatigue / maximum fatigue)

3. fMagicLevelMagnitudeMult
	* Default: 0.250
	* Description: Multiplier for level-based magic effects like Turn Undead, Frenzy, Calm, Command etc. This is the reason why you can't create any spells with a level-magnitude over 25. The maximum magnitude of any spell that is created by spellmaking is limited to 100. This multiplier will turn 100 into 25. Change the value to 1 to allow the creation of level-based spell to effect target's up to level 100. Changing it will alter every existing spell/enchantment.

4. fMagicUnitsPerFoot
	* Default: 22.0
	* Description: Oblivion uses a coordinate system with 'units' as the base form of measurement. When calculating areas of effect, Oblivion uses fMagicUnitsPerFoot to convert the 'feet' attribute of the area of effect into the equivalent units. The default value is 22.0000.

</details>

## Fatigue

<details>
<summary>Fatigue Game Settings</Summary>

[Fatigue Game Settings](https://cs.uesp.net/wiki/Fatigue_Game_Settings)

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

## NPC

<details>

<Summary>NPC Game Settings</Summary>

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


### Ranged Combat

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

## Movement

<details>

<Summary>Movement Game Settings</Summary>

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

## Physics Settings

<details>

<summary>Physics Settings</summary>

### Death Force

1. fDeathForceForceMin
	* Default: 35.0
	* Description: This, along with fDeathForceForceMax, determines how much force is allowed when someone dies.

2. fDeathForceForceMax
	* Default: 85.0
	* Description: This, along with fDeathForceForceMin, determines how much force is allowed when someone dies.

### Explosion Force

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

## Miscellaneous Settings

<details>

<summary>Miscellaneous Settings</summary>

1. fRemoveExcessiveDeadTime
	* Default: 10.0
	* Description: The amount of time between checks to iRemoveExcessDeadCount. Used to remove excess corpses during periods of heavy combat between many actors, to increase performance.

2. iRemoveExcessDeadCount
	* Default: 15
	* Description: The maximum number of dead bodies allowed in the loaded area before they fade out (dissapear).

3. fRemoveExcessiveComplexDeadTime
	* Default: 2.5
	* Description: The amount of time between checks to iRemoveExcessDeadComplexCount when SetSceneIsComplex is used. Used to remove excess corpses during periods of heavy combat between many actors, to increase performance.

4. iRemoveExcessDeadComplexCount
	* Default: 3
	* Description: The maximum number of dead bodies allowed in the loaded area before they fade out (dissapear) if the SetSceneIsComplex scripting function is used.


</details>

## Unknown, Unused and broken Settings

<details>

<summary>Unused Settings</summary>

1. fDemandMult
2. fDemandBase


</details>

<details>

<summary>Unknown Use</summary>

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

Unknown Sun Damage Settings

fMagicSunDamageBaseDamage
fMagicSunDamageMinWeather
fMagicSunDamagePainInitialDelay
fMagicSunDamagePainTimer
fMagicSunDamageScreenGlowMult
fMagicSunDamageScreenGlowRateDown
fMagicSunDamageScreenGlowRateUp

</details>


<details>

<summary>Broken Settings</summary>

1. fDefaultNoticeTextDisplayTime
	* Description: Presumably should set the default time for which a message is displayed on screen, but apparently does not work. This at least is consistent with DisplaySeconds argument for message, which also does not work.


</details>