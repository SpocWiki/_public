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

title: has_best-rating
linkTitle: has_best-rating

keywords: [best-rating]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- best_rating
- best-rating
- bestRating
- has_value_for_best_rating
---

Predicate to describe the Quantity of Rating.

Use it like this: 
- [ #has_/value/_for_best_rating :: Number, Text ] or 
- [ has_value_for_best_rating :: Number, Text ] 

The highest value allowed in this rating system. If bestRating is omitted, 5 is assumed.

Predicate describes that: 
[ #has_/domain  :: Rating ]
( #has_/name :: has_value_for_best_rating )
( #has_/range :: Number, Text )

