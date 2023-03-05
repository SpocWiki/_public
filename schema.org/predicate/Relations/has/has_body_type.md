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
title: has_body_type

linkTitle: has_body_type
keywords: [body, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- body-type
- body_type
- bodyType
- has_body_type
---

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has/_body_type :: QualitativeValue, Text, URL ] or 
- [ has_body_type :: QualitativeValue, Text, URL ] 

Indicates the design and body style of the vehicle (e.g. station wagon, hatchback, etc.).

Relation describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: is_body_type )
( #has_/range :: QualitativeValue, Text, URL )

