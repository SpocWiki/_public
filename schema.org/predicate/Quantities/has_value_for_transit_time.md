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

title: has_transit-time
linkTitle: has_transit-time

keywords: [transit-time]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- transit_time
- transit-time
- transitTime
- has_value_for_transit_time
---

Predicate to describe the Quantity of ShippingDeliveryTime.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_transit_time :: QuantitativeValue ] or 
- [ has_value_for_transit_time :: QuantitativeValue ] 

The typical delay the order has been sent for delivery and the goods reach the final customer. Typical properties: minValue, maxValue, unitCode (d for DAY).

Predicate describes that: 
[ #has_/domain  :: ShippingDeliveryTime ]
( #has_/name :: has_value_for_transit_time )
( #has_/range :: QuantitativeValue )

