# Entity classes
## `CBasicEffect`

### Members
* readonly `m_betType`
* float `m_fWaitTime`
* float `m_fFadeTime`
* bool `m_bFade`
* float `m_fFadeStartTime`
* float `m_fFadeStartAlpha`
* vec3 `m_vNormal`
* vec3 `m_vStretch`
* vec3 `m_vDirection`
* float `m_fDepthSortOffset`
* float `m_fFadeInSpeed`
* float `m_tmSpawn`
* float `m_tmWaitAfterDeath`
* bool `m_bLightSource`
* readonly `m_aoLightAnimation`
* readonly `m_iLightAnimation`
* readonly `m_colMultiplyColor`
* readonly `m_soEffect`
* float `m_fSoundTime`
* readonly `m_eptType`
* float `m_tmWhenShot`
* vec3 `m_vGravity`
* readonly `m_penPrediction`

## `CLight`

### Members
* readonly `m_colColor`
* readonly `m_colAmbient`
* float `m_rFallOffRange`
* float `m_rHotSpotRange`
* readonly `m_itIllumination`
* readonly `m_ltType`
* string `m_strDescription`
* string `m_strName`
* bool `m_bDarkLight`
* float `m_fNearClip`
* float `m_fFarClip`
* bool `m_bSubstractSectorAmbient`
* bool `m_bRenderAsSmallLight`
* readonly `m_lftLensFlare`
* bool `m_bBackground`
* bool `m_bLensFlareOnly`
* string `m_fnmLightAnimation`
* readonly `m_iLightAnimation`
* float `m_tmOffsetPhase`
* readonly `m_aoLightAnimation`
* bool `m_bTargetable`
* bool `m_bDynamic`
* bool `m_bDiffusion`
* string `m_fnmAmbientLightAnimation`
* readonly `m_iAmbientLightAnimation`
* readonly `m_aoAmbientLightAnimation`

## `CProjectile`

Inherits: `CMovableModelEntity`

### Members
* readonly `m_penLauncher`
* readonly `m_prtType`
* readonly `m_pmtMove`
* readonly `m_penParticles`
* readonly `m_penTarget`
* readonly `m_penLastDamaged`
* float `m_fSpeed`
* float `m_fIgnoreTime`
* float `m_fFlyTime`
* float `m_fStartTime`
* float `m_fDamageAmount`
* float `m_fRangeDamageAmount`
* float `m_fDamageHotSpotRange`
* float `m_fDamageFallOffRange`
* float `m_fSoundRange`
* bool `m_bExplode`
* bool `m_bLightSource`
* bool `m_bCanHitHimself`
* bool `m_bCanBeDestroyed`
* float `m_fWaitAfterDeath`
* float `m_aRotateSpeed`
* float `m_tmExpandBox`
* float `m_tmInvisibility`
* readonly `m_iRebounds`
* float `m_fStretch`
* readonly `m_soEffect`
* readonly `m_soExplosion`
* float `m_fGuidedMaxSpeedFactor`
* bool `bLockedOn`
* bool `m_bLeftFlame`
* readonly `m_iTeam`
* readonly `m_penPrediction`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CMovableModelEntity`

Inherits: `CMovableEntity`

### Members
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CMovableEntity`

### Members
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CBloodSpray`

### Members
* readonly `m_sptType`
* float `m_tmStarted`
* vec3 `m_vDirection`
* readonly `m_penOwner`
* float `m_fDamagePower`
* readonly `m_boxSizedOwner`
* vec3 `m_vGDir`
* float `m_fGA`
* float `m_fLaunchPower`
* readonly `m_colCentralColor`
* readonly `m_boxOriginalOwner`
* readonly `m_colBurnColor`
* readonly `m_penPrediction`

## `CFlame`

Inherits: `CMovableModelEntity`

### Members
* readonly `m_penOwner`
* readonly `m_penAttach`
* bool `m_bLoop`
* vec3 `m_vHitPoint`
* readonly `m_soEffect`
* float `m_tmStart`
* float `m_fDamageToApply`
* float `m_fDamageStep`
* float `m_fAppliedDamage`
* float `m_tmFirstStart`
* readonly `m_ctFlames`
* vec3 `m_vPos01`
* vec3 `m_vPos02`
* vec3 `m_vPos03`
* vec3 `m_vPos04`
* vec3 `m_vPos05`
* vec3 `m_vPos06`
* vec3 `m_vPos07`
* vec3 `m_vPos08`
* vec3 `m_vPos09`
* vec3 `m_vPos10`
* vec3 `m_vPlaneNormal`
* bool `m_bBurningBrush`
* float `m_tmDeathParticlesStart`
* readonly `m_penPrediction`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CBullet`

### Members
* readonly `m_penOwner`
* float `m_fDamage`
* vec3 `m_vTarget`
* vec3 `m_vTargetCopy`
* vec3 `m_vHitPoint`
* readonly `m_iBullet`
* readonly `m_EdtDamage`
* float `m_fBulletSize`
* readonly `m_iBatchID`

## `CPlayerWeaponsEffects`

Inherits: `CMovableEntity`

### Members
* readonly `m_penOwner`
* readonly `m_EwetEffect`
* readonly `m_penPrediction`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CGhostBusterRay`

Inherits: `CMovableModelEntity`

### Members
* readonly `m_penOwner`
* bool `m_bRender`
* vec3 `m_vSrcOld`
* vec3 `m_vDstOld`
* vec3 `m_vSrc`
* vec3 `m_vDst`
* vec3 `m_iLastBulletPosition`
* readonly `m_aoLightAnim`
* readonly `m_ctPasses`
* readonly `m_penPrediction`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CCannonBall`

Inherits: `CMovableModelEntity`

### Members
* readonly `m_penLauncher`
* float `m_fLaunchPower`
* float `m_fCannonBallSize`
* float `m_fIgnoreTime`
* float `m_fStartTime`
* readonly `m_iNextChannel`
* bool `m_bSelfExploded`
* readonly `m_soBounce0`
* readonly `m_soBounce1`
* readonly `m_soBounce2`
* readonly `m_soBounce3`
* readonly `m_soBounce4`
* readonly `m_cbtType`
* float `m_tmInvisibility`
* float `m_tmExpandBox`
* float `m_tmForceExplode`
* bool `m_bCheatedLifetime`
* float `m_fCheatedLifetimeValue`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CItem`

Inherits: `CMovableModelEntity`

### Members
* string `m_strName`
* string `m_strDescription`
* float `m_fValue`
* float `m_fRespawnTime`
* float `m_fCustomRespawnTime`
* bool `m_bRespawn`
* readonly `m_penTarget`
* bool `m_bPickupOnce`
* readonly `m_soPick`
* float `m_fPickSoundLen`
* bool `m_bDropped`
* readonly `m_ulPickedMask`
* bool `m_bFloating`
* string `m_fnmCustomModel`
* string `m_fnmCustomTexture`
* float `m_fCustomScale`
* string `m_fnmCustomPickupSound`
* bool `m_bOnlyCoop`
* readonly `m_penPrediction`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CWeaponItem`

Inherits: `CItem`

### Members
* readonly `m_EwitType`
* readonly `m_iAmmoAmount`

### Members inherited from `CItem`
* string `m_strName`
* string `m_strDescription`
* float `m_fValue`
* float `m_fRespawnTime`
* float `m_fCustomRespawnTime`
* bool `m_bRespawn`
* readonly `m_penTarget`
* bool `m_bPickupOnce`
* readonly `m_soPick`
* float `m_fPickSoundLen`
* bool `m_bDropped`
* readonly `m_ulPickedMask`
* bool `m_bFloating`
* string `m_fnmCustomModel`
* string `m_fnmCustomTexture`
* float `m_fCustomScale`
* string `m_fnmCustomPickupSound`
* bool `m_bOnlyCoop`
* readonly `m_penPrediction`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CEnergyMine`

Inherits: `CMovableModelEntity`

### Members
* readonly `m_penLauncher`
* bool `m_bArmed`
* float `m_fSpeed`
* readonly `m_penNextMine`
* bool `m_bExploded`
* float `m_fRange`
* readonly `m_soArming`
* readonly `m_soDetonating`
* readonly `m_penPrediction`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CPlayerWeapons`

### Members
* readonly `m_penPlayer`
* bool `m_bFireWeapon`
* bool `m_bHasAmmo`
* readonly `m_iCurrentWeapon`
* readonly `m_iWantedWeapon`
* readonly `m_iPreviousWeapon`
* readonly `m_iAvailableWeapons`
* bool `m_bChangeWeapon`
* bool `m_bReloadWeapon`
* bool `m_bMirrorFire`
* readonly `m_iAnim`
* float `m_fAnimWaitTime`
* float `m_tmRangeSoundSpawned`
* bool `m_bSniperZoom`
* float `m_fSniperFOV`
* float `m_fSniperFOVlast`
* string `m_strLastTarget`
* float `m_tmTargetingStarted`
* float `m_tmLastTarget`
* float `m_tmSnoopingStarted`
* readonly `m_penTargeting`
* readonly `m_moWeapon`
* readonly `m_moWeaponSecond`
* float `m_tmWeaponChangeRequired`
* readonly `m_penRayHit`
* float `m_fRayHitDistance`
* float `m_fEnemyHealth`
* vec3 `m_vRayHit`
* vec3 `m_vRayHitLast`
* vec3 `m_vBulletSource`
* vec3 `m_vBulletTarget`
* readonly `m_iBullets`
* readonly `m_iMaxBullets`
* readonly `m_iShells`
* readonly `m_iMaxShells`
* readonly `m_iRockets`
* readonly `m_iMaxRockets`
* readonly `m_iGrenades`
* readonly `m_iMaxGrenades`
* readonly `m_iNapalm`
* readonly `m_iMaxNapalm`
* readonly `m_iElectricity`
* readonly `m_iMaxElectricity`
* readonly `m_iIronBalls`
* readonly `m_iMaxIronBalls`
* readonly `m_iSniperBullets`
* readonly `m_iMaxSniperBullets`
* readonly `m_iPlasmaPacks`
* readonly `m_iMaxPlasmaPacks`
* readonly `m_iMinePacks`
* readonly `m_iMaxMinePacks`
* readonly `m_iKnifeStand`
* readonly `m_iColtBullets`
* float `m_aMiniGun`
* float `m_aMiniGunLast`
* float `m_aMiniGunSpeed`
* float `m_aMiniGunSpinLeft`
* vec3 `m_iLastBulletPosition`
* readonly `m_iBulletsOnFireStart`
* float `m_fSniperMaxFOV`
* float `m_fSniperMinFOV`
* float `m_fSnipingZoomSpeed`
* bool `m_bSniping`
* float `m_fMinimumZoomFOV`
* float `m_tmLastSniperFire`
* readonly `m_penFlame`
* readonly `m_iLaserBarrel`
* readonly `m_iPlasmaBarrel`
* readonly `m_penGhostBusterRay`
* readonly `m_iFlare`
* readonly `m_iSecondFlare`
* float `m_tmFlareAdded`
* float `m_tmSecondFlareAdded`
* float `m_fWeaponDrawPowerOld`
* float `m_fWeaponDrawPower`
* float `m_tmDrawStartTime`
* float `m_tmFlamerStart`
* float `m_tmFlamerStop`
* float `m_tmLastChainsawSpray`
* bool `m_bUsedKnifeOnly`
* readonly `m_iTimesFired`
* readonly `m_iTimesHit`
* readonly `m_iBulletBatchID`
* bool `m_bSecFireWeapon`
* bool `m_bPrimaryFire`
* readonly `m_penEnergyMine`
* readonly `m_ctMaxMines`
* float `m_fMinigunTickTime`
* readonly `m_penPrediction`

## `CReminder`

### Members
* readonly `m_penOwner`
* float `m_fWaitTime`
* readonly `m_iValue`

## `CPlayerAnimator`

### Members
* readonly `m_penPlayer`
* bool `m_bReference`
* float `m_fLastActionTime`
* readonly `m_iContent`
* bool `m_bWaitJumpAnim`
* bool `m_bCrouch`
* bool `m_iCrouchDownWait`
* bool `m_iRiseUpWait`
* bool `m_bChangeWeapon`
* bool `m_bSwim`
* readonly `m_iFlare`
* readonly `m_iSecondFlare`
* float `m_tmSecondFlareAdded`
* bool `m_bAttacking`
* float `m_tmAttackingDue`
* float `m_tmFlareAdded`
* bool `m_bDisableAnimating`
* vec3 `m_vLastPlayerPosition`
* float `m_fEyesYLastOffset`
* float `m_fEyesYOffset`
* float `m_fEyesYSpeed`
* float `m_fWeaponYLastOffset`
* float `m_fWeaponYOffset`
* float `m_fWeaponYSpeed`
* bool `m_bMoving`
* float `m_fMoveLastBanking`
* float `m_fMoveBanking`
* bool `m_iMovingSide`
* bool `m_bSidestepBankingLeft`
* bool `m_bSidestepBankingRight`
* float `m_fSidestepLastBanking`
* float `m_fSidestepBanking`
* readonly `m_iWeaponLast`
* float `m_fBodyAnimTime`
* readonly `m_penPrediction`

## `CPlayerView`

Inherits: `CMovableEntity`

### Members
* readonly `m_penOwner`
* readonly `m_iViewType`
* float `m_fDistance`
* vec3 `m_vZLast`
* vec3 `m_vTargetLast`
* bool `m_bFixed`
* readonly `m_penPrediction`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CSeriousBomb`

### Members
* readonly `m_penOwner`
* readonly `m_soBlow`

## `CPlayer`

Inherits: `CPlayerEntity`

### Members
* string `m_strName`
* readonly `m_ulLastButtons`
* float `m_fArmor`
* string `m_strGroup`
* readonly `m_ulKeys`
* float `m_fMaxHealth`
* readonly `m_ulFlags`
* readonly `m_penWeapons`
* readonly `m_penAnimator`
* readonly `m_penView`
* readonly `m_pen3rdPersonView`
* readonly `m_iViewState`
* readonly `m_iLastViewState`
* readonly `m_iViewStateVehicle`
* readonly `m_aoLightAnimation`
* float `m_fDamageAmount`
* float `m_tmWoundedTime`
* float `m_tmScreamTime`
* float `m_tmShitGitTime`
* bool `m_bGotHurt`
* bool `m_bJumped`
* readonly `m_iGender`
* readonly `m_pstState`
* float `m_fFallTime`
* float `m_fSwimTime`
* float `m_tmOutOfWater`
* float `m_tmMoveSound`
* bool `m_bMoveSoundLeft`
* float `m_tmNextAmbientOnce`
* float `m_tmMouthSoundLast`
* readonly `m_penCamera`
* string `m_strCenterMessage`
* float `m_tmCenterMessageEnd`
* bool `m_bPendingMessage`
* float `m_tmMessagePlay`
* float `m_tmAnalyseEnd`
* bool `m_bComputerInvoked`
* float `m_tmAnimateInbox`
* readonly `m_penMainMusicHolder`
* float `m_tmLastDamage`
* float `m_fMaxDamageAmount`
* vec3 `m_vDamage`
* float `m_tmSpraySpawned`
* float `m_fSprayDamage`
* readonly `m_penSpray`
* readonly `m_soWeapon0`
* readonly `m_soWeapon1`
* readonly `m_soWeapon2`
* readonly `m_soWeapon3`
* readonly `m_soWeaponAmbient`
* readonly `m_soPowerUpBeep`
* readonly `m_soMouth`
* readonly `m_soFootL`
* readonly `m_soFootR`
* readonly `m_soBody`
* readonly `m_soLocalAmbientLoop`
* readonly `m_soLocalAmbientOnce`
* readonly `m_soMessage`
* readonly `m_soSpeech`
* readonly `m_soSniperZoom`
* readonly `m_iMana`
* float `m_fManaFraction`
* float `m_tmLatency`
* float `m_tmLatencyLastAvg`
* float `m_tmLatencyAvgSum`
* readonly `m_ctLatencyAvg`
* bool `m_bEndOfLevel`
* bool `m_bEndOfGame`
* readonly `m_iMayRespawn`
* float `m_tmSpawned`
* vec3 `m_vDied`
* vec3 `m_aDied`
* float `m_tmEstTime`
* readonly `m_iTimeScore`
* readonly `m_iStartTime`
* readonly `m_iEndTime`
* float `m_tmLevelStarted`
* string `m_strLevelStats`
* readonly `m_penActionMarker`
* float `m_fAutoSpeed`
* readonly `m_iAutoOrgWeapon`
* vec3 `m_vAutoSpeed`
* float `m_tmSpiritStart`
* float `m_tmFadeStart`
* float `m_tmLastPicked`
* string `m_strPickedName`
* float `m_fPickedAmount`
* float `m_fPickedMana`
* readonly `m_iLastHealth`
* readonly `m_iLastArmor`
* readonly `m_iLastAmmo`
* float `m_tmHealthChanged`
* float `m_tmArmorChanged`
* float `m_tmAmmoChanged`
* float `m_tmMinigunAutoFireStart`
* vec3 `m_vLastStain`
* vec3 `m_aLastRotation`
* vec3 `m_aLastViewRotation`
* vec3 `m_vLastTranslation`
* vec3 `m_aLocalRotation`
* vec3 `m_aLocalViewRotation`
* vec3 `m_vLocalTranslation`
* float `m_tmInvisibility`
* float `m_tmInvulnerability`
* float `m_tmSeriousDamage`
* float `m_tmSeriousSpeed`
* float `m_tmSeriousJump`
* float `m_tmInvisibilityMax`
* float `m_tmInvulnerabilityMax`
* float `m_tmSeriousDamageMax`
* float `m_tmSeriousSpeedMax`
* float `m_tmSeriousJumpMax`
* float `m_tmChainShakeEnd`
* float `m_fChainShakeStrength`
* float `m_fChainShakeFreqMod`
* float `m_fChainsawShakeDX`
* float `m_fChainsawShakeDY`
* readonly `m_iSeriousBombCount`
* readonly `m_iLastSeriousBombCount`
* float `m_tmSeriousBombFired`
* readonly `m_iTeam`
* readonly `m_kaiKills`
* readonly `m_kaiRoundKills`
* float `m_katmLastKill`
* readonly `m_iHasFlag`
* readonly `m_penCarriedFlag`
* readonly `m_soCTFYouHaveTheirFlag`
* readonly `m_soCTFTheyHaveYourFlag`
* readonly `m_soCTFRedTeamScores`
* readonly `m_soCTFBlueTeamScores`
* readonly `m_soCTFRedFlagReturned`
* readonly `m_soCTFBlueFlagReturned`
* readonly `m_soKABackstab`
* readonly `m_soKAHumiliation`
* readonly `m_soKAExcellent`
* readonly `m_soKAMultiKll`
* readonly `m_soKAOwned`
* bool `m_bIsReady`
* float `m_tmStartFadeIn`
* float `m_tmDiedAt`
* float `m_tmGravityStart`
* readonly `m_iBulletBatchIDLastHit`
* readonly `m_penInControlZone`
* float `m_tmFragMade`
* readonly `m_penFragPlayer`
* readonly `m_penInVehicle`
* bool `m_bSelectingTeam`
* bool `m_bWaitingForNextRound`
* readonly `m_penPrediction`

### Members inherited from `CPlayerEntity`
* float `en_tmPing`
* readonly `en_ulSteamID`
* string `en_strSteamName`
* float `en_fDamageDealt`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

## `CPlayerEntity`

Inherits: `CMovableModelEntity`

### Members
* float `en_tmPing`
* readonly `en_ulSteamID`
* string `en_strSteamName`
* float `en_fDamageDealt`

### Members inherited from `CMovableModelEntity`
* readonly `en_iCollisionBox`
* readonly `en_iWantedCollisionBox`

### Members inherited from `CMovableEntity`
* vec3 `en_vDesiredTranslationRelative`
* vec3 `en_aDesiredRotationRelative`
* vec3 `en_vCurrentTranslationAbsolute`
* vec3 `en_aCurrentRotationAbsolute`
* readonly `en_penReference`
* vec3 `en_vReferencePlane`
* readonly `en_iReferenceSurface`
* readonly `en_penLastValidReference`
* float `en_tmLastBreathed`
* float `en_tmMaxHoldBreath`
* float `en_fDensity`
* float `en_tmLastSwimDamage`
* float `en_tmMaxColdness`
* float `en_tmLastWarmth`
* bool `en_bImmuneToCold`
* readonly `en_iUpContent`
* readonly `en_iDnContent`
* float `en_fImmersionFactor`
* vec3 `en_vGravityDir`
* float `en_fGravityA`
* float `en_fGravityV`
* vec3 `en_vForceDir`
* float `en_fForceA`
* float `en_fForceV`
* float `en_tmJumped`
* float `en_tmMaxJumpControl`
* float `en_fJumpControlMultiplier`
* float `en_fAcceleration`
* float `en_fDeceleration`
* float `en_fStepUpHeight`
* float `en_fStepDnHeight`
* float `en_fBounceDampParallel`
* float `en_fBounceDampNormal`
* float `en_fCollisionSpeedLimit`
* float `en_fCollisionDamageFactor`
* readonly `en_boxMovingEstimate`
* readonly `en_boxNearCached`
* vec3 `en_vIntendedTranslation`
* readonly `en_mIntendedRotation`
* readonly `en_iLastForceType`
* float `en_tmLastFrozen`
* float `en_tmFrozenSeconds`
* float `en_tmFrozenMinimum`

