---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate geo
publish: true

# Hugo Tags
type: Pred_geo

title: has_geo_location_from_location
linkTitle: has_geo_location_from_location

keywords: [from_location]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/geo

aliases:
- from-location
- from_location
- fromLocation
- has_geo_location_from_location
---

Predicate to describe the geo of ExerciseAction, MoveAction, TransferAction.

Use it like this: 
- [ #has_/geo/_from_location :: Place ] or 
- [ has_geo_from_location :: Place ] 

A sub property of location. The original location of the object or the agent before the action.

Predicate describes that: 
[ #has_/domain  :: ExerciseAction, MoveAction, TransferAction ]
( #has_/name :: has_geo_location_from_location )
( #has_/range :: Place )

[ #is_/sub_property_of  :: location ]

