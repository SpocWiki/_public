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
title: has_associated_disease

linkTitle: has_associated_disease
keywords: [associated, disease]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- associated-disease
- associated_disease
- associatedDisease
- has_associated_disease
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_associated_disease :: MedicalCondition, PropertyValue, URL ] or 
- [ has_associated_disease :: MedicalCondition, PropertyValue, URL ] 

Disease associated to this BioChemEntity. Such disease can be a MedicalCondition or a URL. If you want to add an evidence supporting the association, please use PropertyValue.

Relation describes that: 
[ #has_/domain  :: BioChemEntity ]
( #has_/name :: is_associated_disease )
( #has_/range :: MedicalCondition, PropertyValue, URL )

