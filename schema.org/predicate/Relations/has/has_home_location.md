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
title: has_home_location

linkTitle: has_home_location
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
- home-location
- home_location
- homeLocation
- has_home_location
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_home_location :: ContactPoint, Place] or 
- [ has_home_location :: ContactPoint, Place] 

A contact location for a person&#x27;s residence.

Relation describes that: 
[ #has_/domain  :: Person]
( #has_/name :: is_home_location)
( #has_/range :: ContactPoint, Place)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: location]

[ #has_/sub_properties :: ]

