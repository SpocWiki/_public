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
title: has_type_of_bed

linkTitle: has_type_of_bed
keywords: [type, of, bed]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- type-of-bed
- type_of_bed
- typeOfBed
- has_type_of_bed
---

Use it like this: 
- [ #has/_type_of_bed :: BedType, Text ] or 
- [ has_type_of_bed :: BedType, Text ] 

The type of bed to which the BedDetail refers, i.e. the type of bed available in the quantity indicated by quantity.

Relation describes that: 
[ #has_/domain  :: BedDetails ]
( #has_/name :: is_type_of_bed )
( #has_/range :: BedType, Text )

