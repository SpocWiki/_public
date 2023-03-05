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
title: has_study_subject

linkTitle: has_study_subject
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
- study-subject
- study_subject
- studySubject
- has_study_subject
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_study_subject :: MedicalEntity] or 
- [ has_study_subject :: MedicalEntity] 

A subject of the study, i.e. one of the medical conditions, therapies, devices, drugs, etc. investigated by the study.

Relation describes that: 
[ #has_/domain  :: MedicalStudy]
( #has_/name :: is_study_subject)
( #has_/range :: MedicalEntity)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

