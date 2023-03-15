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

title: has_eligible-quantity
linkTitle: has_eligible-quantity

keywords: [eligible-quantity]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- eligible_quantity
- eligible-quantity
- eligibleQuantity
- has_value_for_eligible_quantity
---

Predicate to describe the Quantity of Demand, Offer, PriceSpecification.

Use it like this: 
- [ #has_/value/_for_eligible_quantity :: QuantitativeValue ] or 
- [ has_value_for_eligible_quantity :: QuantitativeValue ] 

The interval and unit of measurement of ordering quantities for which the offer or price specification is valid. This allows e.g. specifying that a certain freight charge is valid only for a certain quantity.

Predicate describes that: 
[ #has_/domain  :: Demand, Offer, PriceSpecification ]
( #has_/name :: has_value_for_eligible_quantity )
( #has_/range :: QuantitativeValue )

