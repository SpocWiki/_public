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

title: has_max-price
linkTitle: has_max-price

keywords: [max-price]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- max_price
- max-price
- maxPrice
- has_value_for_max_price
---

Predicate to describe the Quantity of PriceSpecification.

Use it like this: 
- [ #has_/value/_for_max_price :: Number ] or 
- [ has_value_for_max_price :: Number ] 

The highest price if the price is a range.

Predicate describes that: 
[ #has_/domain  :: PriceSpecification ]
( #has_/name :: has_value_for_max_price )
( #has_/range :: Number )

