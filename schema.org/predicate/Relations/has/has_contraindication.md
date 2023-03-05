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
title: has_contraindication

linkTitle: has_contraindication
keywords: [contraindication]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- contraindication
- contraindication
- contraindication
- has_contraindication
---

Use it like this: 
- [ #has/_contraindication :: MedicalContraindication, Text ] or 
- [ has_contraindication :: MedicalContraindication, Text ] 

A contraindication for this therapy.

Relation describes that: 
[ #has_/domain  :: MedicalDevice, MedicalTherapy ]
( #has_/name :: is_contraindication )
( #has_/range :: MedicalContraindication, Text )

