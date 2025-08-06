# Oblivion Remastered Comprehensive GameSettings MCM

# Brief Overview
* A Mod Configuration Menu (MCM) control panel for configuring every functional GameSetting in Oblivion Remastered. 

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

0.4
* Renamed config Files again, sorry - Delete the old ones and use the ones that are numbered.
* Added 0. Obsolete.ini to contain settings that no longer function but still exist.
* Added 47 Stealth settings
* Sneak Attack damage and Combat Damage seemingly are being calculated using different numbers than the OG settings. Sneak Attack Damage settings have been moved to Obsolete. Will continue to test combat settings.

0.5
* Added 5. Magic.ini [41 Settings]; 6. Player.ini [21 Settings]; 7. Player Stats.ini [32 Settings]
* Up to 228 Managed Settings

0.6
* Updated ini file names: Delete old files and copy new.
* Added 6. Player Skills.ini [54 Settings]; 7. NPC.ini [37 Settings]; 8. Physics.ini [36 Settings]; 9. Miscellaneous.ini [53 Settings]
* Up to 408 Managed Settings
* All of the settings defined in the Construction Set Wiki have been added

## Description

* A research project into Oblivion Remastered's GameSettings.
* Currently there is no way to reflect the current settings in the MCM. Hopefully in the future we have a bit more control over what the MCM is displaying. 
	* The values displayed in the MCM are what is being set in INI file. When changed the MCM uses a Console Command to actually set the GameSetting.
	* Default GameSettings are not loaded when the MCM runs.
	
### Compatibility

* The settings in the MCM will only take priority if you manually change them in the MCM, this will update the value in the INI file, forcing it to load that value on future loads. 
* For example, if using my Dynamic Difficulty Multipliers (DDM-MCM) mod, the script will run and set the necessary values depending on whatever your Damage Difficulty Multiplier is set to in that MCM. If you then went into the GameSettings_MCM -> Gameplay ini and changed a difficulty setting, that setting will now take priority and will be set OnLoad of the game. If DDM-MCM is changed again, the new multiplier will be calculated and set the manually set setting as expected. Currently, there is no way for the menu to automatically update values to match what the GameSettings actually are. 

[GameSettings Index](https://github.com/justv316/GameSettings_MCM/blob/main/docs/GameSettings.md)

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

### Updating
0. Copy all files to respective directories overwriting everything (esp and ini files). You shouldn't need to do anything In-game between updates.

### Uninstallation
0. MCM Reset Method
	1. While In-Game, open the MCM, open 0. RestoreDefaults and click Run Command. Close the MCM to trigger the reset. A MessageBox will display, confirming settings have been restored to default. 
	2. You can now safely delete the INI and ESP files.

### Usage
0. In-Game, press your assigned hotkey to open the MCM (Default: L)
1. Click on one of the control panels and configure your settings.

## Roadmap

1. (Waiting on MCM support) Support creating GameSetting profiles for Modders to easily distribute customized GameSetting profiles for their mods. 
2. Continue investigating GameSettings that haven't been defined.

## Research

* If you want to participate in GameSettings research, please feel free to post comments on this Mod's page, send me a DM on Nexus, or if you know me on Discord through one of the many modding communities I am in, ping me there with whatever your findings are!

### Perks
* Many, if not all, of the skill and perk settings have been taken over by UE, and aren't GameSettings anymore.
* These GameSettings have been outright deleted from the game.
fPerkAthleticsNoviceFatigueMult 
fPerkAthleticsApprenticeFatigueMult
fPerkAthleticsJourneymanFatigueMult
fPerkAthleticsExpertFatigueMult 
fPerkAthleticsMasterFatigueMult 
fSneakUnseenMin
fSneakSeenMin

### MCM Files

**__. Obsolete.ini_**

Contains settings that are no longer functional in Oblivion Remastered but still exist in the game.

**_0. RestoreDefault.ini_**

Contains Command to restore all settings to default. This command runs after the MCM is closed. The command cannot be spammed and can only ever be queued to run once. 

**_1. Gameplay.ini [41 Settings]_** 

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

**_2. Combat.ini [46 Settings]_**

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

**_3. Stealth.ini [47 Settings]_**

**Sneak Mechanics**
fSneakBaseValue
iSneakSkillUseDistance
fSneakMaxDistance
fSneakExteriorDistanceMult
fSneakLightMult
fSneakUnseenMin
fSneakSeenMin
fSneakSkillMult
fSneakBootWeightBase
fSneakBootWeightMult
fSneakRunningMult
fSneakSleepBonus
fSneakSoundLosMult
fSneakSoundsMult
fSneakSwimmingLightMult
fSneakTargetAttackBonus
fSneakTargetInCombatBonus
iAICombatMinDetection
fDetectionTimerSetting
fDetectionSneakLightMod
fDetectionNightEyeBonus
fCrimeDispAttack
fCrimeDispMurder
fCrimeDispPickpocket
fCrimeDispSteal
fCrimeDispTresspass
fCrimeDispPersonal
fCrimeGoldSteal
iCrimeGoldAttackMin
iCrimeGoldAttack
iCrimeGoldJailBreak
iCrimeGoldMurder
iCrimeGoldPickpocket
iCrimeGoldStealHorse
iCrimeGoldTresspass
iCrimeGoldMinValue
iCrimeAlarmRecDistance
iNumberGuardsCrimeResponse
iCrimeDaysInPrisonMod

**Lockpicking**
fLockPickAutoBase
iLockLevelMaxVeryEasy
iLockLevelMaxEasy
iLockLevelMaxAverage
iLockLevelMaxHard
iLockLevelMaxVeryHard

**Pickpocket**
fPickPocketMaxChance
fPickPocketMinChance

**_4. Magic.ini [41 Settings]_**

**Magicka Cost**
fMagicCostScale
fMagicAreaBaseCostMult
fMagicDurMagBaseCostMult
fMagicRangeTargetCostMult
fMagicCasterSkillCostBase
fMagicCasterSkillCostMult

**Spellmaking & Enchantment**
fSpellmakingGoldMult
fMagicCEEnchantMagOffset
fEnchantmentGoldMult
fEnchantmentPointsMult
fRechargeGoldMult

**Soulgems**
iSoulLevelValuePetty
fEnchantPettyLimit
iSoulLevelValueLesser
fEnchantLesserLimit
iSoulLevelValueCommon
fEnchantCommonLimit
iSoulLevelValueGreater
fEnchantGreaterLimit
iSoulLevelValueGrand
fEnchantGrandLimit

**Spell Level**
fMagicSpellLevelApprenticeMin
fMagicSpellLevelJourneymanMin
fMagicSpellLevelExpertMin
fMagicSpellLevelMasterMin

**Disease**
fMagicDiseaseTransferBase
fMagicDiseaseTransferMult
fMagicSunDamageSunHiddenScale
fMagicSunDamageWaterScale

**Magic Visuals**
fMagicLightForwardOffset
fMagicLightHeightOffset
fMagicLightHeightOffset
fMagicNightEyeAmbient
fChameleonMaxRefraction
fChameleonMinRefraction
fShockCastVOffset
fShockBoltsRadius

**Uncategorized**
fMagicLevelMagnitudeMult
iMagnitudeLevelAffectsAll
fMagicUnitsPerFoot
iMaxPlayerSummonedCreatures

**_5. Player Stats.ini [53 Settings]_**

**Health**
fPCBaseHealthMult
fStatsHealthStartMult
fStatsHealthLevelMult

**Fatigue**
fFatigueBase
fFatigueMult
fFatigueReturnBase
fFatigueReturnMult
fFatigueRunBase
fFatigueRunMult
fFatigueJumpBase
fFatigueJumpMult
fFatigueCastBase
fFatigueCastMult
fFatigueAttackWeaponBase
fFatigueAttackWeaponMult
fFatigueBlockBase
fFatigueBlockMult
fFatigueBlockSkillBase
fFatigueBlockSkillMult
fPowerAttackFatiguePenalty
fMarksmanFatigueBurnPerSecond
fMarksmanFatigueBurnPerShot
iMarksmanFatigueBurnPerSecondSkill
fPerkJumpFatigueExpertMult
fPerkAthleticsNoviceFatigueMult
fPerkAthleticsApprenticeFatigueMult
fPerkAthleticsJourneymanFatigueMult
fPerkAthleticsExpertFatigueMult
fPerkAthleticsMasterFatigueMult

**Magicka**
fPCBaseMagickaMult
fMagickaReturnBase
fMagickaReturnMult

**Skills**
fTrainingCostMult
iTrainingSkills
fSkillUseExp
fSkillUseFactor
fSkillUseMajorMult
fSkillUseMinorMult
fSkillUseSpecMult
iSkillApprenticeMin
iSkillJourneymanMin
iSkillExpertMin
iSkillMasterMin

**Perks**
iPerkMarksmanParalyzeChance
iPerkMarksmanKnockdownChance
iPerkHandToHandBlockRecoilChance
iPerkExtraBarterGoldMaster
iPerkBlockStaggerChance
iPerkBlockDisarmChance
iPerkAttackDisarmChance

**Attributes**
fAttributeClassPrimaryBonus
fAttributeClassSecondaryBonus

**Levels**
iLevelUpSkillCount

**_6. Player Skill.ini [54 Settings]_**

**Barter**
fBarterBuyBase
fBarterBuyMult
fBarterSellBase
fBarterSellMult
fBarterDispBase
fBarterHaggleBase
fBarterHaggleCurve
fBarterHaggleDispMult
fBarterHaggleMax
iMerchantRespawnDay1
iMerchantRespawnDay2

**Bribery**
fBribeCostCurve
fBribeScale
fBribeCurve
fBribeNPCLevelMult
fBribeSpeechcraftMult

**Repair**
fRepairArmorerBase
fRepairArmorerMult
fRepairStrengthMult
fRepairSkillBreakBase
fRepairSkillBreakMult
fRepairCostMult
iArmorDamageBootsChance
iArmorDamageCuirassChance
iArmorDamageGauntletsChance
iArmorDamageGreavesChance
iArmorDamageHelmChance
iArmorDamageShieldChance

**Alchemy**
fPotionMortPestleMult
fPotionT1MagMult
fPotionT1AleDurMult
fPotionT1AleMagMult
fPotionT1CalMagMult
fPotionT1RetDurMult
fPotionT1RetMagMult
fPotionT2AleDurMult
fPotionT2CalDurMult
fPotionT2RetDurMult
fPotionT3AleMagMult
fPotionT3CalMagMult
fPotionT3RetMagMult
fPotionGoldValueMult
iMagicMaxPotionsNovice
iMagicMaxPotionsApprentice
iMagicMaxPotionsJourneyman
iMagicMaxPotionsExpert
iMagicMaxPotionsMaster

**Wortcraft**
fWortAlchMult
fWortcraftFatigueMag
iWortcraftMaxEffectsNovice
iWortcraftMaxEffectsApprentice
iWortcraftMaxEffectsJourneyman
iWortcraftMaxEffectsExpert
iWortcraftMaxEffectsMaster

**_7. NPC.ini [37 Settings]_**

**NPC**
fNPCBaseMagickaMult
fNPCAttributeHealthMult
fEnemyHealthBarTimer
fEssentialDeathTime
fEssentialHealthPercentReGain
fMinDistanceUseHorse
fFleeDistanceExterior
fFleeDistanceInterior
fDistanceExteriorReactCombat
fDistanceInteriorReactCombat
fHostileActorExteriorDistance
fHostileActorInteriorDistance

**AI**
fAITalktoNPCTimer
fAITalktoSameNPCtimer
fAIMaxWanderTime
fAIFleeConfBase
fAIFleeConfMult
fAIFleeHealthMult
iAIDefaultMeleeAlertAllowed
iAIDefaultPowerAttackBackwardChance
iAINPCRacePowerChance

**Ranged Combat**
fArrowOptimalDistance
fArrowMaxDistance
fMagicBallOptimalDistance
fMagicBallMaximumDistance
fMagicBoltOptimalDistance
fMagicBoltMaximumDistance
fMagicFogOptimalDistance
fMagicFogMaximumDistance
fMagicSprayOptimalDistance
fMagicSprayMaximumDistance
fMagicProjectileBaseSpeed
fMagicProjectileMaxDistance

**Blink**
fBlinkDelayMax
fBlinkDelayMin
fBlinkDownTime
fBlinkUpTime

**_8. Physics.ini [36 Settings]_**

**Physics**
fObjectHitWeaponReach
fObjectHitWeaponReach

**Arrows**
fArrowAgeMax
fArrowBounceLinearSpeed
fArrowBounceRotateSpeed
fArrowFakeMass
fArrowFOVTimeChange
fArrowFOVTimeStart
fArrowFOVZoom
fArrowGravityBase
fArrowGravityMin
fArrowGravityMult
fArrowSpeedMult
fArrowBowTimerBase
fArrowBowTimerBase
fArrowWeakGravity
fArrowWeakSpeed
iArrowInventoryChance
iArrowMaxRefCount

**Death Force**
fDeathForceForceMin
fDeathForceForceMax

**Explosion Force**
fMagicExplosionPowerMin
fMagicExplosionPowerMax
fMagicExplosionPowerMult

**Buoyancy**
fBuoyancyWater
fBuoyancyCloth
fBuoyancyDirt
fBuoyancyGlass
fBuoyancyGrass
fBuoyancyMetal
fBuoyancyOrganic
fBuoyancySkin
fBuoyancyStone
fBuoyancyWood
fBuoyancyMultBody
fBuoyancyMultExtremity

**_9. Miscellaneous.ini [53 Settings]_**

**Miscellaneous**
iInventoryAskQuantityAt
iMaxArrowsInQuiver

**Clothing**
fClothingArmorBase
fClothingArmorScale
fClothingBase
fClothingClassScale
fClothingJewelryBase
fClothingJewelryScale

**Stars**
fStarsRotateDays
fStarsRotateXAxis
fStarsRotateYAxis
fStarsRotateZAxis

**Movement**
fMoveCharWalkMin
fMoveCharWalkMax
fMoveCreatureWalkMin
fMoveCreatureWalkMax
fMoveEncumEffect
fMoveEncumEffectNoWea
fMoveWeightMin
fMoveWeightMax
fMoveNoWeaponMult
fMoveRunMult
fMoveRunAthleticsMult
fMoveSneakMult
fPerkHeavyArmorExpertSpeedMult
fPerkHeavyArmorMasterSpeedMult
fPerkHeavyArmorSinkGravityMult
fPerkLightArmorExpertSpeedMult
fArmorWeightLightMaxMod
fMoveSwimWalkBase
fMoveSwimWalkAthleticsMult
fMoveSwimRunBase
fMoveSwimRunAthleticsMult
fSubmergedMaxSpeed
fMoveMinFlySpeed
fMoveMaxFlySpeed

**Falling**
fJumpFallSkillBase
fJumpFallSkillMult
fJumpFallTimeBase
fJumpFallTimeMin
fJumpFallTimeMult
fJumpFallVelocityMin
fJumpHeightMax
fJumpHeightMin
fJumpMoveBase
fJumpMoveBase

**Camera**
fVanityModeWheelMult
fVanityModeWheelMax
fVanityModeWheelMin
fVanityModeXMult
fVanityModeYMult
fVanityModeDelay
fChase3rdPersonZUnitsPerSecond

## Credits
1. Utilizes ObScript Extender created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)
2. Utilizes MCM created by [MadAborModding](https://next.nexusmods.com/profile/MadAborModding)