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
title: has_main_entity

linkTitle: has_main_entity
keywords: [main, entity]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- main-entity
- main_entity
- mainEntity
- has_main_entity
---

Use it like this: 
- [ #has/_main_entity :: Thing ] or 
- [ has_main_entity :: Thing ] 

Indicates the primary entity described in some page or other CreativeWork.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_main_entity )
( #has_/range :: Thing )

[ #is_/inverse_of  :: [[is_main_entity_of_page]] ]

[ #is_/sub_property_of  :: about ]

