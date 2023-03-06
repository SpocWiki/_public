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

title: has_has-measurement
linkTitle: has_has-measurement

keywords: [has-measurement]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- measurement
- has-measurement
- hasMeasurement
- has_value_for_measurement
---

Predicate to describe the Quantity of Offer, Product, SizeSpecification.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_measurement :: QuantitativeValue ] or 
- [ has_value_for_measurement :: QuantitativeValue ] 

A product measurement, for example the inseam of pants, the wheel size of a bicycle, or the gauge of a screw. Usually an exact measurement, but can also be a range of measurements for adjustable products, for example belts and ski bindings.

Predicate describes that: 
[ #has_/domain  :: Offer, Product, SizeSpecification ]
( #has_/name :: has_value_for_measurement )
( #has_/range :: QuantitativeValue )

