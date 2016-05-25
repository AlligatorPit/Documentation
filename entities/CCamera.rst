CCamera
=======

Inherits: `CMovableModelEntity <CMovableModelEntity.html>`_

.. include:: ../entities_info/CCamera.rst

Members
-------

* float ``m_tmTime``
* float ``m_fFOV``
* float ``m_fLastFOV``
* readonly ``m_penTarget``
* string ``m_strName``
* readonly ``m_penOnBreak``
* bool ``m_bWideScreen``
* float ``m_tmAtMarker``
* float ``m_tmDelta``
* vec3 ``m_vPNp0``
* vec3 ``m_vPNp1``
* vec3 ``m_vTNp0``
* vec3 ``m_vTNp1``
* float ``m_fFOVp0``
* float ``m_fFOVp1``
* float ``m_fTFOVp0``
* float ``m_fTFOVp1``
* readonly ``m_qPNp0``
* readonly ``m_qPNp1``
* readonly ``m_qANp0``
* readonly ``m_qANp1``
* readonly ``m_penLast``
* readonly ``m_penPlayer``
* string ``m_strDescription``
* bool ``m_bStopMoving``
* readonly ``m_colFade0``
* readonly ``m_colFade1``
* bool ``m_bMoving``
* readonly ``m_penViewTarget0``
* readonly ``m_penViewTarget1``
* vec3 ``m_vPosRatio0``
* vec3 ``m_vPosRatio1``
* float ``m_fMyTimer``
* float ``m_fMyTimerLast``
* bool ``m_bIgnoreTimeStretch``
* bool ``m_bAutoRotation``
* float ``m_fStartHdg``
* float ``m_fRotateSpeed``
* float ``m_fRotateTime``
* float ``m_fRadX``
* float ``m_fHeight``
* float ``m_fRadZ``
* readonly ``m_penAutoCameraEndTarget``
* readonly ``m_eetAutoCameraEndEvent``
* vec3 ``m_vRelTargetOffset``

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

