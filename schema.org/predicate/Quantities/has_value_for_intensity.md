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

title: has_intensity
linkTitle: has_intensity

keywords: [intensity]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- intensity
- intensity
- intensity
- has_value_for_intensity
---

Predicate to describe the Quantity of ExercisePlan.

Use it like this: 
- [ #has_/value/_for_intensity :: QuantitativeValue, Text ] or 
- [ has_value_for_intensity :: QuantitativeValue, Text ] 

Quantitative measure gauging the degree of force involved in the exercise, for example, heartbeats per minute. May include the velocity of the movement.

Predicate describes that: 
[ #has_/domain  :: ExercisePlan ]
( #has_/name :: has_value_for_intensity )
( #has_/range :: QuantitativeValue, Text )

