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

title: has_duration-of-warranty
linkTitle: has_duration-of-warranty

keywords: [duration-of-warranty]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- duration_of_warranty
- duration-of-warranty
- durationOfWarranty
- has_value_for_duration_of_warranty
---

Predicate to describe the Quantity of WarrantyPromise.

Use it like this: 
- [ #has_/value/_for_duration_of_warranty :: QuantitativeValue ] or 
- [ has_value_for_duration_of_warranty :: QuantitativeValue ] 

The duration of the warranty promise. Common unitCode values are ANN for year, MON for months, or DAY for days.

Predicate describes that: 
[ #has_/domain  :: WarrantyPromise ]
( #has_/name :: has_value_for_duration_of_warranty )
( #has_/range :: QuantitativeValue )

