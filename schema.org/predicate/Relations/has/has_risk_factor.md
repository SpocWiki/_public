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
title: has_risk_factor

linkTitle: has_risk_factor
keywords: [risk, factor]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- risk-factor
- risk_factor
- riskFactor
- has_risk_factor
---

Use it like this: 
- [ #has/_risk_factor :: MedicalRiskFactor ] or 
- [ has_risk_factor :: MedicalRiskFactor ] 

A modifiable or non-modifiable factor that increases the risk of a patient contracting this condition, e.g. age,  coexisting condition.

Relation describes that: 
[ #has_/domain  :: MedicalCondition ]
( #has_/name :: is_risk_factor )
( #has_/range :: MedicalRiskFactor )

