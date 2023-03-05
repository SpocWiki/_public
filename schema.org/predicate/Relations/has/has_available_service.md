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
title: has_available_service

linkTitle: has_available_service
keywords: [available, service]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- available-service
- available_service
- availableService
- has_available_service
---

Use it like this: 
- [ #has/_available_service :: MedicalProcedure, MedicalTest, MedicalTherapy ] or 
- [ has_available_service :: MedicalProcedure, MedicalTest, MedicalTherapy ] 

A medical service available from this provider.

Relation describes that: 
[ #has_/domain  :: Hospital, MedicalClinic, Physician ]
( #has_/name :: is_available_service )
( #has_/range :: MedicalProcedure, MedicalTest, MedicalTherapy )

