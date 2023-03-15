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

title: has_max-value
linkTitle: has_max-value

keywords: [max-value]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- max_value
- max-value
- maxValue
- has_value_for_max_value
---

Predicate to describe the Quantity of MonetaryAmount, PropertyValue, PropertyValueSpecification, QuantitativeValue.

Use it like this: 
- [ #has_/value/_for_max_value :: Number ] or 
- [ has_value_for_max_value :: Number ] 

The upper value of some characteristic or property.

Predicate describes that: 
[ #has_/domain  :: MonetaryAmount, PropertyValue, PropertyValueSpecification, QuantitativeValue ]
( #has_/name :: has_value_for_max_value )
( #has_/range :: Number )

