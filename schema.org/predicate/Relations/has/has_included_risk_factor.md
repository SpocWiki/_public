---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_included_risk_factor

linkTitle: has_included_risk_factor
keywords: [included, risk, factor]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- included-risk-factor
- included_risk_factor
- includedRiskFactor
- has_included_risk_factor
---

Use it like this: 
- [ #has/_included_risk_factor :: MedicalRiskFactor ] or 
- [ has_included_risk_factor :: MedicalRiskFactor ] 

A modifiable or non-modifiable risk factor included in the calculation, e.g. age, coexisting condition.

Relation describes that: 
[ #has_/domain  :: MedicalRiskEstimator ]
( #has_/name :: has_included_risk_factor )
( #has_/range :: MedicalRiskFactor )

