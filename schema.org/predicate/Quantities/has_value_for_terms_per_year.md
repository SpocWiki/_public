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

title: has_terms-per-year
linkTitle: has_terms-per-year

keywords: [terms-per-year]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- terms_per_year
- terms-per-year
- termsPerYear
- has_value_for_terms_per_year
---

Predicate to describe the Quantity of EducationalOccupationalProgram.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_terms_per_year :: Number ] or 
- [ has_value_for_terms_per_year :: Number ] 

The number of times terms of study are offered per year. Semesters and quarters are common units for term. For example, if the student can only take 2 semesters for the program in one year, then termsPerYear should be 2.

Predicate describes that: 
[ #has_/domain  :: EducationalOccupationalProgram ]
( #has_/name :: has_value_for_terms_per_year )
( #has_/range :: Number )

