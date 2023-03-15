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

title: has_number_of_number_of_credits
linkTitle: has_number_of_number_of_credits

keywords: [number_of_credits]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Count

aliases:
- number-of-credits
- number_of_credits
- numberOfCredits
- has_number_of_credits
---

Predicate to describe the Number of Course, EducationalOccupationalProgram.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/number/_of_credits :: Integer, StructuredValue ] or 
- [ has_number_of_credits :: Integer, StructuredValue ] 

The number of credits or units awarded by a Course or required to complete an EducationalOccupationalProgram.

Predicate describes that: 
[ #has_/domain  :: Course, EducationalOccupationalProgram ]
( #has_/name :: has_number_of_credits )
( #has_/range :: Integer, StructuredValue )

