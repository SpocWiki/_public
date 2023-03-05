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
title: has_food_establishment

linkTitle: has_food_establishment
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- food-establishment
- food_establishment
- foodEstablishment
- has_food_establishment
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_food_establishment :: FoodEstablishment, Place] or 
- [ has_food_establishment :: FoodEstablishment, Place] 

A sub property of location. The specific food establishment where the action occurred.

Relation describes that: 
[ #has_/domain  :: CookAction]
( #has_/name :: is_food_establishment)
( #has_/range :: FoodEstablishment, Place)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: location]

[ #has_/sub_properties :: ]

