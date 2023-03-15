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

title: has_rest-periods
linkTitle: has_rest-periods

keywords: [rest-periods]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- rest_periods
- rest-periods
- restPeriods
- has_value_for_rest_periods
---

Predicate to describe the Quantity of ExercisePlan.

Use it like this: 
- [ #has_/value/_for_rest_periods :: QuantitativeValue, Text ] or 
- [ has_value_for_rest_periods :: QuantitativeValue, Text ] 

How often one should break from the activity.

Predicate describes that: 
[ #has_/domain  :: ExercisePlan ]
( #has_/name :: has_value_for_rest_periods )
( #has_/range :: QuantitativeValue, Text )

