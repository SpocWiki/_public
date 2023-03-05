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
title: has_recorded_at

linkTitle: has_recorded_at
keywords: [recorded, at]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- recorded-at
- recorded_at
- recordedAt
- has_recorded_at
---

Use it like this: 
- [ #has/_recorded_at :: Event ] or 
- [ has_recorded_at :: Event ] 

The Event where the CreativeWork was recorded. The CreativeWork may capture all or part of the event.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_recorded_at )
( #has_/range :: Event )

[ #is_/inverse_of  :: recordedIn ]

