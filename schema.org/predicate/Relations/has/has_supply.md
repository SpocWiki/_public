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
title: has_supply

linkTitle: has_supply
keywords: [supply]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- supply
- supply
- supply
- has_supply
---

Use it like this: 
- [ #has/_supply :: HowToSupply, Text ] or 
- [ has_supply :: HowToSupply, Text ] 

A sub-property of instrument. A supply consumed when performing instructions or a direction.

Relation describes that: 
[ #has_/domain  :: HowTo, HowToDirection ]
( #has_/name :: is_supply )
( #has_/range :: HowToSupply, Text )

[ #is_/sub_property_of  :: instrument ]

[ #has_/sub_properties :: [ ingredients, recipeIngredient ] ]

