CPlayer
=======

Inherits: `CPlayerEntity <CPlayerEntity>`_

Description
-----------

n/a

Members
-------

* string ``m_strName``
* readonly ``m_ulLastButtons``
* float ``m_fArmor``
* string ``m_strGroup``
* readonly ``m_ulKeys``
* float ``m_fMaxHealth``
* readonly ``m_ulFlags``
* readonly ``m_penWeapons``
* readonly ``m_penAnimator``
* readonly ``m_penView``
* readonly ``m_pen3rdPersonView``
* readonly ``m_iViewState``
* readonly ``m_iLastViewState``
* readonly ``m_iViewStateVehicle``
* readonly ``m_aoLightAnimation``
* float ``m_fDamageAmount``
* float ``m_tmWoundedTime``
* float ``m_tmScreamTime``
* float ``m_tmShitGitTime``
* bool ``m_bGotHurt``
* bool ``m_bJumped``
* readonly ``m_iGender``
* readonly ``m_pstState``
* float ``m_fFallTime``
* float ``m_fSwimTime``
* float ``m_tmOutOfWater``
* float ``m_tmMoveSound``
* bool ``m_bMoveSoundLeft``
* float ``m_tmNextAmbientOnce``
* float ``m_tmMouthSoundLast``
* readonly ``m_penCamera``
* string ``m_strCenterMessage``
* float ``m_tmCenterMessageEnd``
* bool ``m_bPendingMessage``
* float ``m_tmMessagePlay``
* float ``m_tmAnalyseEnd``
* bool ``m_bComputerInvoked``
* float ``m_tmAnimateInbox``
* readonly ``m_penMainMusicHolder``
* float ``m_tmLastDamage``
* float ``m_fMaxDamageAmount``
* vec3 ``m_vDamage``
* float ``m_tmSpraySpawned``
* float ``m_fSprayDamage``
* readonly ``m_penSpray``
* readonly ``m_soWeapon0``
* readonly ``m_soWeapon1``
* readonly ``m_soWeapon2``
* readonly ``m_soWeapon3``
* readonly ``m_soWeaponAmbient``
* readonly ``m_soPowerUpBeep``
* readonly ``m_soMouth``
* readonly ``m_soFootL``
* readonly ``m_soFootR``
* readonly ``m_soBody``
* readonly ``m_soLocalAmbientLoop``
* readonly ``m_soLocalAmbientOnce``
* readonly ``m_soMessage``
* readonly ``m_soSpeech``
* readonly ``m_soSniperZoom``
* readonly ``m_iMana``
* float ``m_fManaFraction``
* float ``m_tmLatency``
* float ``m_tmLatencyLastAvg``
* float ``m_tmLatencyAvgSum``
* readonly ``m_ctLatencyAvg``
* bool ``m_bEndOfLevel``
* bool ``m_bEndOfGame``
* readonly ``m_iMayRespawn``
* float ``m_tmSpawned``
* vec3 ``m_vDied``
* vec3 ``m_aDied``
* float ``m_tmEstTime``
* readonly ``m_iTimeScore``
* readonly ``m_iStartTime``
* readonly ``m_iEndTime``
* float ``m_tmLevelStarted``
* string ``m_strLevelStats``
* readonly ``m_penActionMarker``
* float ``m_fAutoSpeed``
* readonly ``m_iAutoOrgWeapon``
* vec3 ``m_vAutoSpeed``
* float ``m_tmSpiritStart``
* float ``m_tmFadeStart``
* float ``m_tmLastPicked``
* string ``m_strPickedName``
* float ``m_fPickedAmount``
* float ``m_fPickedMana``
* readonly ``m_iLastHealth``
* readonly ``m_iLastArmor``
* readonly ``m_iLastAmmo``
* float ``m_tmHealthChanged``
* float ``m_tmArmorChanged``
* float ``m_tmAmmoChanged``
* float ``m_tmMinigunAutoFireStart``
* vec3 ``m_vLastStain``
* vec3 ``m_aLastRotation``
* vec3 ``m_aLastViewRotation``
* vec3 ``m_vLastTranslation``
* vec3 ``m_aLocalRotation``
* vec3 ``m_aLocalViewRotation``
* vec3 ``m_vLocalTranslation``
* float ``m_tmInvisibility``
* float ``m_tmInvulnerability``
* float ``m_tmSeriousDamage``
* float ``m_tmSeriousSpeed``
* float ``m_tmSeriousJump``
* float ``m_tmInvisibilityMax``
* float ``m_tmInvulnerabilityMax``
* float ``m_tmSeriousDamageMax``
* float ``m_tmSeriousSpeedMax``
* float ``m_tmSeriousJumpMax``
* float ``m_tmChainShakeEnd``
* float ``m_fChainShakeStrength``
* float ``m_fChainShakeFreqMod``
* float ``m_fChainsawShakeDX``
* float ``m_fChainsawShakeDY``
* readonly ``m_iSeriousBombCount``
* readonly ``m_iLastSeriousBombCount``
* float ``m_tmSeriousBombFired``
* readonly ``m_iTeam``
* readonly ``m_kaiKills``
* readonly ``m_kaiRoundKills``
* float ``m_katmLastKill``
* readonly ``m_iHasFlag``
* readonly ``m_penCarriedFlag``
* readonly ``m_soCTFYouHaveTheirFlag``
* readonly ``m_soCTFTheyHaveYourFlag``
* readonly ``m_soCTFRedTeamScores``
* readonly ``m_soCTFBlueTeamScores``
* readonly ``m_soCTFRedFlagReturned``
* readonly ``m_soCTFBlueFlagReturned``
* readonly ``m_soKABackstab``
* readonly ``m_soKAHumiliation``
* readonly ``m_soKAExcellent``
* readonly ``m_soKAMultiKll``
* readonly ``m_soKAOwned``
* bool ``m_bIsReady``
* float ``m_tmStartFadeIn``
* float ``m_tmDiedAt``
* float ``m_tmGravityStart``
* readonly ``m_iBulletBatchIDLastHit``
* readonly ``m_penInControlZone``
* float ``m_tmFragMade``
* readonly ``m_penFragPlayer``
* readonly ``m_penInVehicle``
* bool ``m_bSelectingTeam``
* bool ``m_bWaitingForNextRound``
* readonly ``m_penPrediction``

Members inherited from CPlayerEntity
------------------------------------

* float ``en_tmPing``
* readonly ``en_ulSteamID``
* string ``en_strSteamName``
* float ``en_fDamageDealt``

Members inherited from CMovableModelEntity
------------------------------------------

* readonly ``en_iCollisionBox``
* readonly ``en_iWantedCollisionBox``

Members inherited from CMovableEntity
-------------------------------------

* vec3 ``en_vDesiredTranslationRelative``
* vec3 ``en_aDesiredRotationRelative``
* vec3 ``en_vCurrentTranslationAbsolute``
* vec3 ``en_aCurrentRotationAbsolute``
* readonly ``en_penReference``
* vec3 ``en_vReferencePlane``
* readonly ``en_iReferenceSurface``
* readonly ``en_penLastValidReference``
* float ``en_tmLastBreathed``
* float ``en_tmMaxHoldBreath``
* float ``en_fDensity``
* float ``en_tmLastSwimDamage``
* float ``en_tmMaxColdness``
* float ``en_tmLastWarmth``
* bool ``en_bImmuneToCold``
* readonly ``en_iUpContent``
* readonly ``en_iDnContent``
* float ``en_fImmersionFactor``
* vec3 ``en_vGravityDir``
* float ``en_fGravityA``
* float ``en_fGravityV``
* vec3 ``en_vForceDir``
* float ``en_fForceA``
* float ``en_fForceV``
* float ``en_tmJumped``
* float ``en_tmMaxJumpControl``
* float ``en_fJumpControlMultiplier``
* float ``en_fAcceleration``
* float ``en_fDeceleration``
* float ``en_fStepUpHeight``
* float ``en_fStepDnHeight``
* float ``en_fBounceDampParallel``
* float ``en_fBounceDampNormal``
* float ``en_fCollisionSpeedLimit``
* float ``en_fCollisionDamageFactor``
* readonly ``en_boxMovingEstimate``
* readonly ``en_boxNearCached``
* vec3 ``en_vIntendedTranslation``
* readonly ``en_mIntendedRotation``
* readonly ``en_iLastForceType``
* float ``en_tmLastFrozen``
* float ``en_tmFrozenSeconds``
* float ``en_tmFrozenMinimum``

