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
title: is_part_of_order

linkTitle: is_part_of_order
keywords: [part, of, order]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-order
- part_of_order
- partOfOrder
- is_part_of_order
---

Use it like this: 
- [ #is/_part_of_order :: Order ] or 
- [ is_part_of_order :: Order ] 

The overall order the items in this delivery were included in.

Relation describes that: 
[ #has_/domain  :: ParcelDelivery ]
( #has_/name :: is_part_of_order )
( #has_/range :: Order )

