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
title: has_related_condition

linkTitle: has_related_condition
keywords: [related, condition]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- related-condition
- related_condition
- relatedCondition
- has_related_condition
---

Use it like this: 
- [ #has/_related_condition :: MedicalCondition ] or 
- [ has_related_condition :: MedicalCondition ] 

A medical condition associated with this anatomy.

Relation describes that: 
[ #has_/domain  :: AnatomicalStructure, AnatomicalSystem, SuperficialAnatomy ]
( #has_/name :: is_related_condition )
( #has_/range :: MedicalCondition )

