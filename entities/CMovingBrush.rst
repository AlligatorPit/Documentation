CMovingBrush
============

Inherits: `CMovableEntity <CMovableEntity.html>`_

.. include:: ../entities_info/CMovingBrush.rst

Members
-------

* string ``m_strName``
* string ``m_strDescription``
* readonly ``m_penTarget``
* bool ``m_bAutoStart``
* float ``m_fSpeed``
* float ``m_fWaitTime``
* bool ``m_bMoveOnTouch``
* readonly ``m_ebaAction``
* float ``m_fBlockDamage``
* bool ``m_bPlayersOnly``
* bool ``m_bDynamicShadows``
* bool ``m_bVeryBigBrush``
* readonly ``m_eetTouchEvent``
* readonly ``m_penTouchEvent``
* readonly ``m_tdeSendEventOnDamage``
* readonly ``m_penSwitch``
* readonly ``m_eetMarkerEvent``
* readonly ``m_penMarkerEvent``
* float ``m_tmBankingRotation``
* bool ``m_bMoving``
* bool ``m_bRotating``
* bool ``m_bForceStop``
* bool ``m_bNoRotation``
* vec3 ``m_vDesiredTranslation``
* vec3 ``m_aDesiredRotation``
* bool ``m_bInverseRotate``
* bool ``m_bStopMoving``
* bool ``m_bMoveToMarker``
* bool ``m_bSkipMarker``
* bool ``m_bValidMarker``
* float ``m_fXLimitSign``
* float ``m_fYLimitSign``
* float ``m_fZLimitSign``
* readonly ``m_aHLimitSign``
* readonly ``m_aPLimitSign``
* readonly ``m_aBLimitSign``
* vec3 ``m_vStartTranslation``
* vec3 ``m_aStartRotation``
* float ``m_fCourseLength``
* readonly ``m_aHeadLenght``
* readonly ``m_aPitchLenght``
* readonly ``m_aBankLenght``
* readonly ``m_penSoundStart``
* readonly ``m_penSoundStop``
* readonly ``m_penSoundFollow``
* readonly ``m_soStart``
* readonly ``m_soStop``
* readonly ``m_soFollow``
* readonly ``m_penMirror0``
* readonly ``m_penMirror1``
* readonly ``m_penMirror2``
* readonly ``m_penMirror3``
* readonly ``m_penMirror4``
* float ``m_fHealth``
* bool ``m_bBlowupByBull``
* readonly ``m_eetBlowupEvent``
* readonly ``m_penBlowupEvent``
* bool ``m_bZoning``
* bool ``m_bMoveOnDamage``
* float ``m_fTouchDamage``
* readonly ``m_colDebrises``
* readonly ``m_ctDebrises``
* float ``m_fCandyEffect``
* float ``m_fCubeFactor``
* bool ``m_bBlowupByDamager``
* readonly ``m_cbClassificationBits``
* readonly ``m_vbVisibilityBits``

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

