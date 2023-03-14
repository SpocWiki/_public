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
title: has_health_condition

linkTitle: has_health_condition
keywords: [health, condition]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- health-condition
- health_condition
- healthCondition
- has_health_condition
---

Use it like this: 
- [ #has/_health_condition :: MedicalCondition ] or 
- [ has_health_condition :: MedicalCondition ] 

Specifying the health condition(s) of a patient, medical study, or other target audience.

Relation describes that: 
[ #has_/domain  :: MedicalStudy, Patient, PeopleAudience ]
( #has_/name :: has_health_condition )
( #has_/range :: MedicalCondition )

