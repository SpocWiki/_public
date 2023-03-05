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
title: has_engine_type

linkTitle: has_engine_type
keywords: [engine, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- engine-type
- engine_type
- engineType
- has_engine_type
---

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has/_engine_type :: QualitativeValue, Text, URL ] or 
- [ has_engine_type :: QualitativeValue, Text, URL ] 

The type of engine or engines powering the vehicle.

Relation describes that: 
[ #has_/domain  :: EngineSpecification ]
( #has_/name :: is_engine_type )
( #has_/range :: QualitativeValue, Text, URL )

