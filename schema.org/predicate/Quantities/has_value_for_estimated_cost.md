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

title: has_estimated-cost
linkTitle: has_estimated-cost

keywords: [estimated-cost]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- estimated_cost
- estimated-cost
- estimatedCost
- has_value_for_estimated_cost
---

Predicate to describe the Quantity of HowTo, HowToSupply.

Use it like this: 
- [ #has_/value/_for_estimated_cost :: MonetaryAmount, Text ] or 
- [ has_value_for_estimated_cost :: MonetaryAmount, Text ] 

The estimated cost of the supply or supplies consumed when performing instructions.

Predicate describes that: 
[ #has_/domain  :: HowTo, HowToSupply ]
( #has_/name :: has_value_for_estimated_cost )
( #has_/range :: MonetaryAmount, Text )

