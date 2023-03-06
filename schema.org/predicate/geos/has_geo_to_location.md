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

title: has_geo_location_to_location
linkTitle: has_geo_location_to_location

keywords: [to_location]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- to-location
- to_location
- toLocation
- has_geo_location_to_location
---

Predicate to describe the geo of ExerciseAction, InsertAction, MoveAction, TransferAction.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_to_location :: Place ] or 
- [ has_geo_to_location :: Place ] 

A sub property of location. The final location of the object or the agent after the action.

Predicate describes that: 
[ #has_/domain  :: ExerciseAction, InsertAction, MoveAction, TransferAction ]
( #has_/name :: has_geo_location_to_location )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  :: location ]

[ #has_/sub_properties :: [  ] ]

