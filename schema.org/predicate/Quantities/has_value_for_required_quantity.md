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

title: has_required-quantity
linkTitle: has_required-quantity

keywords: [required-quantity]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- required_quantity
- required-quantity
- requiredQuantity
- has_value_for_required_quantity
---

Predicate to describe the Quantity of HowToItem.

Use it like this: 
- [ #has_/value/_for_required_quantity :: Number, QuantitativeValue, Text ] or 
- [ has_value_for_required_quantity :: Number, QuantitativeValue, Text ] 

The required quantity of the item(s).

Predicate describes that: 
[ #has_/domain  :: HowToItem ]
( #has_/name :: has_value_for_required_quantity )
( #has_/range :: Number, QuantitativeValue, Text )

