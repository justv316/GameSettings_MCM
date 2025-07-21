# Game Settings


	
## Damage

### Power Attack Maneuvers

fDamagePowerAttackBackBonus
	Default: 2.50
	Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

fDamagePowerAttackForwardBonus
	Default: 2.50
	Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.
	
fDamagePowerAttackSideBonus
	Default: 2.50
	Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.
	
fDamagePowerAttackStandBonus
	Default: 3.00
	Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

fDamagePowerAttackBonus
	Default: 2.50
	Description: For each of the power attack maneuvers, there is a damage multiplier. The damage normally done is multiplied by this game setting before being applied to the target. Damage is always a floating point value, so decimals are not rounded.

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
	* Description: Used to calculate the damage-multiplier received from attributes. For BLUNT and BLADE weapons the actor's current Strength is used
	For MARKSMAN the actor's current agility is used. Both are capped at 100, meaning that fortifying your strength over 100 won't result in more damage.

4. fDamageStrengthMult
5. fDamageToArmorPercentage
6. fDamageToWeaponPercentage
7. fDamageWeaponConditionBase
8. fDamageWeaponConditionMult
9. fDamageWeaponMult

## Stealth

### Sneak Damage

fDamageSneakAttackMult
	Default: No Default
	Description:  multiplies the base attack by this value before applying the damage to an enemy. It is activated when a player initiates an attack while in sneak mode, thus the "Sneak Attack x#" message when you perform a sneak attack on an enemy. This value is a base value for sneak attacks and is further modified by a character's sneak skill, weapon type (melee or ranged), attack direction (front, back, side, sleep), and attack type (normal or power). Each of these modifiers has its own setting.
	
## Magic	
	
### Soulgems

iSoulLevelValuePetty
    Default: 150
	Description: Charge Provided by Petty Soulgems
	
iSoulLevelValueLesser
    Default: 300
	Description: Charge Provided by Lesser Soulgems

iSoulLevelValueCommon
    Default: 800
	Description: Charge Provided by Common Soulgems
	
iSoulLevelValueGreater
    Default: 1200
	Description: Charge Provided by Greater Soulgems

iSoulLevelValueGrand
    Default: 1600
	Description: Charge Provided by Grand Soulgems