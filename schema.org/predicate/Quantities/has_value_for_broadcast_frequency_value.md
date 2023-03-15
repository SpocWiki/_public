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

title: has_broadcast-frequency-value
linkTitle: has_broadcast-frequency-value

keywords: [broadcast-frequency-value]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- broadcast_frequency_value
- broadcast-frequency-value
- broadcastFrequencyValue
- has_value_for_broadcast_frequency_value
---

Predicate to describe the Quantity of BroadcastFrequencySpecification.

Use it like this: 
- [ #has_/value/_for_broadcast_frequency_value :: Number, QuantitativeValue ] or 
- [ has_value_for_broadcast_frequency_value :: Number, QuantitativeValue ] 

The frequency in MHz for a particular broadcast.

Predicate describes that: 
[ #has_/domain  :: BroadcastFrequencySpecification ]
( #has_/name :: has_value_for_broadcast_frequency_value )
( #has_/range :: Number, QuantitativeValue )

