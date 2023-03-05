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
keywords: [study, subject]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- study-subject
- study_subject
- studySubject
- has_study_subject
---

Use it like this: 
- [ #has/_study_subject :: MedicalEntity ] or 
- [ has_study_subject :: MedicalEntity ] 

A subject of the study, i.e. one of the medical conditions, therapies, devices, drugs, etc. investigated by the study.

Relation describes that: 
[ #has_/domain  :: MedicalStudy ]
( #has_/name :: is_study_subject )
( #has_/range :: MedicalEntity )

