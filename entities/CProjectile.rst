CProjectile
===========

Inherits: `CMovableModelEntity <CMovableModelEntity.html>`_

.. include:: ../entities_info/CProjectile.rst

Members
-------

* readonly ``m_penLauncher``
* readonly ``m_prtType``
* readonly ``m_pmtMove``
* readonly ``m_penParticles``
* readonly ``m_penTarget``
* readonly ``m_penLastDamaged``
* float ``m_fSpeed``
* float ``m_fIgnoreTime``
* float ``m_fFlyTime``
* float ``m_fStartTime``
* float ``m_fDamageAmount``
* float ``m_fRangeDamageAmount``
* float ``m_fDamageHotSpotRange``
* float ``m_fDamageFallOffRange``
* float ``m_fSoundRange``
* bool ``m_bExplode``
* bool ``m_bLightSource``
* bool ``m_bCanHitHimself``
* bool ``m_bCanBeDestroyed``
* float ``m_fWaitAfterDeath``
* float ``m_aRotateSpeed``
* float ``m_tmExpandBox``
* float ``m_tmInvisibility``
* readonly ``m_iRebounds``
* float ``m_fStretch``
* readonly ``m_soEffect``
* readonly ``m_soExplosion``
* float ``m_fGuidedMaxSpeedFactor``
* bool ``bLockedOn``
* bool ``m_bLeftFlame``
* readonly ``m_iTeam``
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

