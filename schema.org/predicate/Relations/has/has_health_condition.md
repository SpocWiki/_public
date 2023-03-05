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
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- health-condition
- health_condition
- healthCondition
- has_health_condition
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_health_condition :: MedicalCondition] or 
- [ has_health_condition :: MedicalCondition] 

Specifying the health condition(s) of a patient, medical study, or other target audience.

Relation describes that: 
[ #has_/domain  :: MedicalStudy, Patient, PeopleAudience]
( #has_/name :: is_health_condition)
( #has_/range :: MedicalCondition)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
