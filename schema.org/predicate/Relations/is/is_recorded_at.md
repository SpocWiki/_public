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
title: is_recorded_at

linkTitle: is_recorded_at
keywords: [recorded, at]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- recorded-at
- recorded_at
- recordedAt
- is_recorded_at
---

Use it like this: 
- [ #is/_recorded_at :: Event ] or 
- [ is_recorded_at :: Event ] 

The Event where the CreativeWork was recorded. The CreativeWork may capture all or part of the event.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_recorded_at )
( #has_/range :: [[../../../Type/is_a_thing/event]] )

[ #is_/inverse_of  :: recordedIn ]

