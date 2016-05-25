CBeast
======

Inherits: `CEnemyBase <CEnemyBase.html>`_

.. include:: ../entities_info/CBeast.rst

Members
-------

* readonly ``m_bcType``
* readonly ``m_iCounter``
* bool ``m_bBeBoss``

Members inherited from CEnemyBase
---------------------------------

* readonly ``m_penWatcher``
* vec3 ``m_vStartPosition``
* readonly ``m_penEnemy``
* readonly ``m_ttTarget``
* string ``m_strDescription``
* string ``m_strName``
* readonly ``m_soSound``
* vec3 ``m_vStartDirection``
* bool ``m_bOnStartPosition``
* float ``m_fFallHeight``
* float ``m_fStepHeight``
* float ``m_fSenseRange``
* float ``m_fViewAngle``
* float ``m_fWalkSpeed``
* readonly ``m_aWalkRotateSpeed``
* float ``m_fAttackRunSpeed``
* readonly ``m_aAttackRotateSpeed``
* float ``m_fCloseRunSpeed``
* readonly ``m_aCloseRotateSpeed``
* float ``m_fAttackDistance``
* float ``m_fCloseDistance``
* float ``m_fAttackFireTime``
* float ``m_fCloseFireTime``
* float ``m_fStopDistance``
* float ``m_fIgnoreRange``
* float ``m_fLockOnEnemyTime``
* float ``m_fBlowUpAmount``
* readonly ``m_fBodyParts``
* float ``m_fDamageWounded``
* vec3 ``m_vDamage``
* float ``m_tmLastDamage``
* bool ``m_bRobotBlowup``
* float ``m_fBlowUpSize``
* float ``m_fMoveTime``
* vec3 ``m_vDesiredPosition``
* readonly ``m_dtDestination``
* readonly ``m_penPathMarker``
* vec3 ``m_vPlayerSpotted``
* float ``m_fMoveFrequency``
* float ``m_fMoveSpeed``
* readonly ``m_aRotateSpeed``
* float ``m_fLockStartTime``
* float ``m_fRangeLast``
* bool ``m_bFadeOut``
* float ``m_fFadeStartTime``
* float ``m_fFadeTime``
* float ``m_fShootTime``
* float ``m_fDamageConfused``
* readonly ``m_iChargeHitAnimation``
* float ``m_fChargeHitDamage``
* float ``m_fChargeHitAngle``
* float ``m_fChargeHitSpeed``
* readonly ``m_penSpawnerTarget``
* readonly ``m_penDeathTarget``
* readonly ``m_eetDeathType``
* bool ``m_bTemplate``
* float ``m_fAttackRadius``
* readonly ``m_colColor``
* bool ``m_bDeaf``
* bool ``m_bBlind``
* float ``m_tmGiveUp``
* float ``m_tmReflexMin``
* float ``m_tmReflexMax``
* float ``m_fActivityRange``
* bool ``m_bApplyRandomStretch``
* float ``m_fRandomStretchFactor``
* float ``m_fStretchMultiplier``
* float ``m_fRandomStretchMultiplier``
* readonly ``m_penMarker``
* readonly ``m_penMainMusicHolder``
* float ``m_tmLastFussTime``
* float ``m_iScore``
* float ``m_fMaxHealth``
* bool ``m_bBoss``
* float ``m_fSpiritStartTime``
* float ``m_tmSpraySpawned``
* float ``m_fSprayDamage``
* readonly ``m_penSpray``
* float ``m_fMaxDamageAmount``
* vec3 ``m_vLastStain``
* readonly ``m_sptType``
* readonly ``m_penTacticsHolder``
* bool ``m_bTacticActive``
* float ``m_tmTacticsActivation``
* vec3 ``m_vTacticsStartPosition``
* float ``m_fTacticVar1``
* float ``m_fTacticVar2``
* float ``m_fTacticVar3``
* float ``m_fTacticVar4``
* float ``m_fTacticVar5``
* bool ``m_bTacticsStartOnSense``
* readonly ``m_colBurning``
* bool ``m_bResizeAttachments``
* bool ``m_bGiveUpToClosestMarker``
* string ``m_fnmCustomModel``
* string ``m_fnmCustomTexture``
* bool ``m_bUseCustomWeaponProjectile``
* readonly ``m_eCustomWeaponProjectile``
* readonly ``m_iCustomScore``
* string ``m_fnmCustomMessage``
* bool ``m_bShootHitscansInsteadOfProjectiles``
* float ``m_fCustomHitscansDamage``
* readonly ``m_penStartEnemy``
* readonly ``m_eetEnvironmentType``
* float ``m_fHealthScalar``
* readonly ``m_penPrediction``

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

