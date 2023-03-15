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

title: has_dose-value
linkTitle: has_dose-value

keywords: [dose-value]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- dose_value
- dose-value
- doseValue
- has_value_for_dose_value
---

Predicate to describe the Quantity of DoseSchedule.

Use it like this: 
- [ #has_/value/_for_dose_value :: Number, QualitativeValue ] or 
- [ has_value_for_dose_value :: Number, QualitativeValue ] 

The value of the dose, e.g. 500.

Predicate describes that: 
[ #has_/domain  :: DoseSchedule ]
( #has_/name :: has_value_for_dose_value )
( #has_/range :: Number, QualitativeValue )

