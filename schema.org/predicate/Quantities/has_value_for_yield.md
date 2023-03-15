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

title: has_yield
linkTitle: has_yield

keywords: [yield]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- yield
- yield
- yield
- has_value_for_yield
---

Predicate to describe the Quantity of HowTo.

Use it like this: 
- [ #has_/value/_for_yield :: QuantitativeValue, Text ] or 
- [ has_value_for_yield :: QuantitativeValue, Text ] 

The quantity that results by performing instructions. For example, a paper airplane, 10 personalized candles.

Predicate describes that: 
[ #has_/domain  :: HowTo ]
( #has_/name :: has_value_for_yield )
( #has_/range :: QuantitativeValue, Text )

[ #has_/sub_properties :: [ recipeYield ] ]

