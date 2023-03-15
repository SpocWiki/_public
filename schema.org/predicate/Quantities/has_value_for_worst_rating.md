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

title: has_worst-rating
linkTitle: has_worst-rating

keywords: [worst-rating]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- worst_rating
- worst-rating
- worstRating
- has_value_for_worst_rating
---

Predicate to describe the Quantity of Rating.

Use it like this: 
- [ #has_/value/_for_worst_rating :: Number, Text ] or 
- [ has_value_for_worst_rating :: Number, Text ] 

The lowest value allowed in this rating system. If worstRating is omitted, 1 is assumed.

Predicate describes that: 
[ #has_/domain  :: Rating ]
( #has_/name :: has_value_for_worst_rating )
( #has_/range :: Number, Text )

