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
title: has_game_availability_type

linkTitle: has_game_availability_type
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
- game-availability-type
- game_availability_type
- gameAvailabilityType
- has_game_availability_type
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_game_availability_type :: GameAvailabilityEnumeration, Text] or 
- [ has_game_availability_type :: GameAvailabilityEnumeration, Text] 

Indicates the availability type of the game content associated with this action, such as whether it is a full version or a demo.

Relation describes that: 
[ #has_/domain  :: PlayGameAction]
( #has_/name :: is_game_availability_type)
( #has_/range :: GameAvailabilityEnumeration, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
