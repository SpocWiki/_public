---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Count
publish: true

# Hugo Tags
type: Predi_Count

title: has_number_of_num_adults
linkTitle: has_number_of_num_adults

keywords: [num_adults]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Count

aliases:
- num-adults
- num_adults
- numAdults
- has_number_of_adults
---

Predicate to describe the Number of LodgingReservation.

Use it like this: 
- [ #has_/number/_of_adults :: Integer, QuantitativeValue ] or 
- [ has_number_of_adults :: Integer, QuantitativeValue ] 

The number of adults staying in the unit.

Predicate describes that: 
[ #has_/domain  :: LodgingReservation ]
( #has_/name :: has_number_of_adults )
( #has_/range :: Integer, QuantitativeValue )

