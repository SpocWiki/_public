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

title: has_number_of_num_children
linkTitle: has_number_of_num_children

keywords: [num_children]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- num-children
- num_children
- numChildren
- has_number_of_children
---

Predicate to describe the Number of LodgingReservation.

Use it like this: 
- [ #has_/number/_of_children :: Integer, QuantitativeValue ] or 
- [ has_number_of_children :: Integer, QuantitativeValue ] 

The number of children staying in the unit.

Predicate describes that: 
[ #has_/domain  :: LodgingReservation ]
( #has_/name :: has_number_of_children )
( #has_/range :: Integer, QuantitativeValue )

