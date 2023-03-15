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

title: has_engine-displacement
linkTitle: has_engine-displacement

keywords: [engine-displacement]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- engine_displacement
- engine-displacement
- engineDisplacement
- has_value_for_engine_displacement
---

Predicate to describe the Quantity of EngineSpecification.

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has_/value/_for_engine_displacement :: QuantitativeValue ] or 
- [ has_value_for_engine_displacement :: QuantitativeValue ] 

The volume swept by all of the pistons inside the cylinders of an internal combustion engine in a single movement. &lt;br/&gt;&lt;br/&gt;

Typical unit code(s): CMQ for cubic centimeter, LTR for liters, INQ for cubic inches
* Note 1: You can link to information about how the given value has been determined using the [[valueReference]] property.
* Note 2: You can use [[minValue]] and [[maxValue]] to indicate ranges.

Predicate describes that: 
[ #has_/domain  :: EngineSpecification ]
( #has_/name :: has_value_for_engine_displacement )
( #has_/range :: QuantitativeValue )

