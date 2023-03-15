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
title: has_normal_range

linkTitle: has_normal_range
keywords: [normal, range]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- normal-range
- normal_range
- normalRange
- has_normal_range
---

Use it like this: 
- [ #has/_normal_range :: MedicalEnumeration, Text ] or 
- [ has_normal_range :: MedicalEnumeration, Text ] 

Range of acceptable values for a typical patient, when applicable.

Relation describes that: 
[ #has_/domain  :: MedicalTest ]
( #has_/name :: has_normal_range )
( #has_/range :: MedicalEnumeration, Text )

