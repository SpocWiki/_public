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
title: has_food_event

linkTitle: has_food_event
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
- food-event
- food_event
- foodEvent
- has_food_event
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_food_event :: FoodEvent] or 
- [ has_food_event :: FoodEvent] 

A sub property of location. The specific food event where the action occurred.

Relation describes that: 
[ #has_/domain  :: CookAction]
( #has_/name :: is_food_event)
( #has_/range :: FoodEvent)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: location]

[ #has_/sub_properties :: ]
