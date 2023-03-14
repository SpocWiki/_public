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
title: is_applicable_in_location

linkTitle: is_applicable_in_location
keywords: [applicable, location]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- applicable-location
- applicable_location
- applicableLocation
- is_applicable_in_location
---

Use it like this: 
- [ #has/_applicable_location :: AdministrativeArea ] or 
- [ is_applicable_in_location :: AdministrativeArea ] 

The location in which the status applies.

Relation describes that: 
[ #has_/domain  :: DrugCost, DrugLegalStatus ]
( #has_/name :: is_applicable_in_location )
( #has_/range :: AdministrativeArea )

