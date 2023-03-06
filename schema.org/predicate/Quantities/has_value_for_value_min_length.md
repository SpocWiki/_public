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

title: has_value-min-length
linkTitle: has_value-min-length

keywords: [value-min-length]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- value_min_length
- value-min-length
- valueMinLength
- has_value_for_value_min_length
---

Predicate to describe the Quantity of PropertyValueSpecification.

Use it like this: 
- [ #has_/value/_for_value_min_length :: Number ] or 
- [ has_value_for_value_min_length :: Number ] 

Specifies the minimum allowed range for number of characters in a literal value.

Predicate describes that: 
[ #has_/domain  :: PropertyValueSpecification ]
( #has_/name :: has_value_for_value_min_length )
( #has_/range :: Number )

