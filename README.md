# Oblivion Remastered Comprehensive GameSettings MCM

# Changelog
0.1
* Release of the first batch of settings. 
0.2 
* Renamed First ini file to Gameplay_GameSettings.ini
* Added 14 actor settings
0.3 
* Up to 87 Managed Settings!!
* Added Combat_GameSettings.ini and GameSettings_MCM.esp
* Added 46 Combat settings
* Added Reset to Default button that will restore all managed settings to default. Currently cannot reset the displayed values in MCM without manually clicking the reset button on the setting, waiting on MCM functionality to support that!
* The plugin file contains the scripts used to support the Reset to Default mechanism and will be used in the future to support certain settings. 

## Description

* A Mod Configuration Menu (MCM) control panel for configuring every functional GameSetting in Oblivion Remastered. 
* Designed as a research project into Oblivion Remastered's GameSettings.
	* This project will continue to be updated as settings are checked to see if they are still functional in Oblivion Remastered.
* Currently there is no way to reflect the current settings in the MCM. Hopefully in the future we have a bit more control over what the MCM is displaying. 
	* The values displayed in the MCM are what is being set in INI file. When changed the MCM uses a Console Command to actually set the GameSetting.
	* Default GameSettings are not loaded when the MCM runs.

## Roadmap

1. Add support for the remaining ~300 GameSettings
2. Create documentation and support creating GameSetting profiles for Modders to easily distribute customized GameSetting profiles for their mods. 
3. Add Restore to Default method for all Managed GameSettings (This will require an esp)
	1. Currently, each setting has a 'Reset' button to return it back to its default value, but I will need to create a mechanism to reset all settings back to default for uninstallations, this will also help modders who use this as a resource to ensure their mods can be safely removed.

## Research

* If you want to participate in GameSettings research, please feel free to post comments on this Mod's page, send me a DM on Nexus, or if you know me on Discord through one of the many modding communities I am in, ping me there with whatever your findings are!

### Prerequisites
1. [UE4SS](https://www.nexusmods.com/oblivionremastered/mods/32)
	1. [Mad OBScript Extender v2.0a or Later](https://www.nexusmods.com/oblivionremastered/mods/4819)
	2. [Mad Config Menu MCM v3.6 or Later](https://www.nexusmods.com/oblivionremastered/mods/4810)
2. [OBSE](https://www.nexusmods.com/oblivionremastered/mods/282)
	1. [NL-Tag Remover](https://www.nexusmods.com/oblivionremastered/mods/473)
	
### Installation
0. Install Prerequisites
1. Copy \OblivionRemastered\ to `\Oblivion Remastered\`
	1. Or copy the contents of \MadConfigs\ to `\Oblivion Remastered\OblivionRemastered\Binaries\Win64\MadConfigs\`
	2. Copy GameSettings_MCM.esp to `\Oblivion Remastered\OblivionRemastered\Content\Dev\ObvData\Data
2. Add GameSettings_MCM.esp to your Plugins.txt

### Uninstallation
0. MCM Reset Method
	1. While In-Game, Open the ResetDefault_Gamesettings MCM and click Run Command. Close the MCM to trigger the reset. A MessageBox will display, confirming settings have been restored to default. 
	2. You can now safely delete the INI and ESP files.

### Usage
0. In-Game, press your assigned hotkey to open the MCM (Default: L)
1. Click on one of the control panels and configure your settings.

### Currently Supported Settings

**_Gameplay_GameSettings.ini_**

**Difficulty**

fDifficultyDamageTakenMultiplierNovice
fDifficultyDamageTakenMultiplierApprentice
fDifficultyDamageTakenMultiplierAdept
fDifficultyDamageTakenMultiplierJourneyman
fDifficultyDamageTakenMultiplierExpert
fDifficultyDamageTakenMultiplierMaster
fDifficultyDamageDealtMultiplierNovice
fDifficultyDamageDealtMultiplierApprentice
fDifficultyDamageDealtMultiplierAdept
fDifficultyDamageDealtMultiplierJourneyman
fDifficultyDamageDealtMultiplierExpert
fDifficultyDamageDealtMultiplierMaster

**Level Scaling**

iLevCreaLevelDifferenceMax
iLevItemLevelDifferenceMax
iLowLevelNPCMaxLevel

**Player World Interaction**

iMapMarkerRevealDistance
iMapMarkerVisibleDistance
iHoursToRespawnCell
iAllowRepairDuringCombat
iAllowRechargeDuringCombat
iAllowAlchemyDuringCombat
fPlayerDropDistance
fPlayerDeathReloadTime
iRemoveExcessDeadComplexCount
fRemoveExcessiveComplexDeadTime
iRemoveExcessDeadCount
fRemoveExcessiveDeadTime

**Actors**

iNumberActorsAllowedToFollowPlayer
iNumberActorsInCombatPlayer
iDeathDropWeaponChance
iFriendHitAllowed
iAllyHitAllowed
iActorLuckSkillBase
fActorLuckSkillMult
fActorStrengthEncumbranceMult
fActorSwimBreathBase
fActorSwimBreathMult
fActorSwimBreathDamage
iVampirismAgeOffset
fActorTeleportFadeSeconds
fActorAnimZAdjust

**_Combat_GameSettings.ini_**

**Damage**

fDamageWeaponMult
fDamageSkillBase
fDamageSkillMult
fDamageStrengthBase
fDamageStrengthMult
fDamageWeaponConditionBase
fDamageWeaponConditionMult
fDamageToArmorPercentage
fDamageToWeaponPercentage
fCombatHitConeAngle

**Power Attack**
fPowerAttackDelay
fDamagePowerAttackBonus
fDamagePowerAttackBackBonus
fDamagePowerAttackForwardBonus
fDamagePowerAttackSideBonus
fDamagePowerAttackStandBonus

**Hand-To-Hand**
fHandDamageSkillBase
fHandDamageSkillMult
fHandDamageStrengthBase
fHandDamageStrengthMult
fHandFatigueDamageBase
fHandFatigueDamageMult
fHandHealthMax
fHandHealthMin
fHandReachMult

**Knockdown**
fKnockbackAgilBase
fKnockbackAgilBase
fKnockbackDamageBase
fKnockbackDamageMult
fKnockbackForceMax
fKnockbackTime
fKnockdownChance

**Block**
fBlockMax
fBlockSkillBase
fBlockSkillMult
fBlockAmountHandToHandMult
fBlockAmountWeaponMult

**Armor**
fMaxArmorRating
fArmorRatingConditionBase
fArmorRatingConditionMult
fArmorRatingBase
fArmorRatingMax

**Combat Speech**
fCombatSpeakAttackChance
fCombatSpeakHitChance
fCombatSpeakHitThreshold
fCombatSpeakPowerAttackChance


## Credits
1. Utilizes ObScript Extender created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)
2. Utilizes MCM created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)