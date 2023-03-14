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
title: is_used_to_diagnose

linkTitle: is_used_to_diagnose
keywords: [used, to, diagnose]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- used-to-diagnose
- used_to_diagnose
- usedToDiagnose
- is_used_to_diagnose
---

Use it like this: 
- [ #is/_used_to_diagnose :: MedicalCondition ] or 
- [ is_used_to_diagnose :: MedicalCondition ] 

A condition the test is used to diagnose.

Relation describes that: 
[ #has_/domain  :: MedicalTest ]
( #has_/name :: is_used_to_diagnose )
( #has_/range :: MedicalCondition )

