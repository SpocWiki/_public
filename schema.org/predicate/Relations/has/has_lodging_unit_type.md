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
title: has_lodging_unit_type

linkTitle: has_lodging_unit_type
keywords: [lodging, unit, type]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- lodging-unit-type
- lodging_unit_type
- lodgingUnitType
- has_lodging_unit_type
---

Use it like this: 
- [ #has/_lodging_unit_type :: QualitativeValue, Text ] or 
- [ has_lodging_unit_type :: QualitativeValue, Text ] 

Textual description of the unit type (including suite vs. room, size of bed, etc.).

Relation describes that: 
[ #has_/domain  :: LodgingReservation ]
( #has_/name :: is_lodging_unit_type )
( #has_/range :: QualitativeValue, Text )

