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

title: has_min-value
linkTitle: has_min-value

keywords: [min-value]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- min_value
- min-value
- minValue
- has_value_for_min_value
---

Predicate to describe the Quantity of MonetaryAmount, PropertyValue, PropertyValueSpecification, QuantitativeValue.

Use it like this: 
- [ #has_/value/_for_min_value :: Number ] or 
- [ has_value_for_min_value :: Number ] 

The lower value of some characteristic or property.

Predicate describes that: 
[ #has_/domain  :: MonetaryAmount, PropertyValue, PropertyValueSpecification, QuantitativeValue ]
( #has_/name :: has_value_for_min_value )
( #has_/range :: Number )

