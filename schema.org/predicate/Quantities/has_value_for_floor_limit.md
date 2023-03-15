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

title: has_floor-limit
linkTitle: has_floor-limit

keywords: [floor-limit]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- floor_limit
- floor-limit
- floorLimit
- has_value_for_floor_limit
---

Predicate to describe the Quantity of PaymentCard.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_floor_limit :: MonetaryAmount ] or 
- [ has_value_for_floor_limit :: MonetaryAmount ] 

A floor limit is the amount of money above which credit card transactions must be authorized.

Predicate describes that: 
[ #has_/domain  :: PaymentCard ]
( #has_/name :: has_value_for_floor_limit )
( #has_/range :: MonetaryAmount )

