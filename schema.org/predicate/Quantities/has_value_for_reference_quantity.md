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

title: has_reference-quantity
linkTitle: has_reference-quantity

keywords: [reference-quantity]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- reference_quantity
- reference-quantity
- referenceQuantity
- has_value_for_reference_quantity
---

Predicate to describe the Quantity of UnitPriceSpecification.

Use it like this: 
- [ #has_/value/_for_reference_quantity :: QuantitativeValue ] or 
- [ has_value_for_reference_quantity :: QuantitativeValue ] 

The reference quantity for which a certain price applies, e.g. 1 EUR per 4 kWh of electricity. This property is a replacement for unitOfMeasurement for the advanced cases where the price does not relate to a standard unit.

Predicate describes that: 
[ #has_/domain  :: UnitPriceSpecification ]
( #has_/name :: has_value_for_reference_quantity )
( #has_/range :: QuantitativeValue )

