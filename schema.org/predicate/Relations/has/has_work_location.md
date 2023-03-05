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
title: has_work_location

linkTitle: has_work_location
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
- work-location
- work_location
- workLocation
- has_work_location
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_work_location :: ContactPoint, Place] or 
- [ has_work_location :: ContactPoint, Place] 

A contact location for a person&#x27;s place of work.

Relation describes that: 
[ #has_/domain  :: Person]
( #has_/name :: is_work_location)
( #has_/range :: ContactPoint, Place)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: location]

[ #has_/sub_properties :: ]
