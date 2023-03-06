---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Quantity
publish: true

# Hugo Tags
type: Predi_Quantity

title: has_material-extent
linkTitle: has_material-extent

keywords: [material-extent]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- material_extent
- material-extent
- materialExtent
- has_value_for_material_extent
---

Predicate to describe the Quantity of CreativeWork.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_material_extent :: QuantitativeValue, Text ] or 
- [ has_value_for_material_extent :: QuantitativeValue, Text ] 

The quantity of the materials being described or an expression of the physical space they occupy.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_value_for_material_extent )
( #has_/range :: QuantitativeValue, Text )

