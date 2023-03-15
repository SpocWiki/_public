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

title: has_min-price
linkTitle: has_min-price

keywords: [min-price]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- min_price
- min-price
- minPrice
- has_value_for_min_price
---

Predicate to describe the Quantity of PriceSpecification.

Use it like this: 
- [ #has_/value/_for_min_price :: Number ] or 
- [ has_value_for_min_price :: Number ] 

The lowest price if the price is a range.

Predicate describes that: 
[ #has_/domain  :: PriceSpecification ]
( #has_/name :: has_value_for_min_price )
( #has_/range :: Number )

