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
title: has_size_group

linkTitle: has_size_group
keywords: [size, group]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- size-group
- size_group
- sizeGroup
- has_size_group
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_size_group :: SizeGroupEnumeration, Text ] or 
- [ has_size_group :: SizeGroupEnumeration, Text ] 

The size group (also known as "size type") for a product's size. Size groups are common in the fashion industry to define size segments and suggested audiences for wearable products. Multiple values can be combined, for example "men's big and tall", "petite maternity" or "regular"

Relation describes that: 
[ #has_/domain  :: SizeSpecification ]
( #has_/name :: is_size_group )
( #has_/range :: SizeGroupEnumeration, Text )

