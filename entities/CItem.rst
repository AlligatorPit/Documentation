CItem
=====

Inherits: `CMovableModelEntity <CMovableModelEntity>`_

Description
-----------

n/a

Members
-------

* string ``m_strName``
* string ``m_strDescription``
* float ``m_fValue``
* float ``m_fRespawnTime``
* float ``m_fCustomRespawnTime``
* bool ``m_bRespawn``
* readonly ``m_penTarget``
* bool ``m_bPickupOnce``
* readonly ``m_soPick``
* float ``m_fPickSoundLen``
* bool ``m_bDropped``
* readonly ``m_ulPickedMask``
* bool ``m_bFloating``
* string ``m_fnmCustomModel``
* string ``m_fnmCustomTexture``
* float ``m_fCustomScale``
* string ``m_fnmCustomPickupSound``
* bool ``m_bOnlyCoop``
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

