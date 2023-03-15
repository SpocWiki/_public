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

title: has_trailer-weight
linkTitle: has_trailer-weight

keywords: [trailer-weight]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- trailer_weight
- trailer-weight
- trailerWeight
- has_value_for_trailer_weight_kg
---

Predicate to describe the Quantity of Vehicle.

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has_/value/_for_trailer_weight_kg :: QuantitativeValue ] or 
- [ has_value_for_trailer_weight_kg :: QuantitativeValue ] 

The permitted weight of a trailer attached to the vehicle.&lt;br/&gt;&lt;br/&gt;

Typical unit code(s): KGM for kilogram, LBR for pound
* Note 1: You can indicate additional information in the [[name]] of the [[QuantitativeValue]] node.
* Note 2: You may also link to a [[QualitativeValue]] node that provides additional information using [[valueReference]].
* Note 3: Note that you can use [[minValue]] and [[maxValue]] to indicate ranges.

Predicate describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: has_value_for_trailer_weight_kg )
( #has_/range :: QuantitativeValue )

