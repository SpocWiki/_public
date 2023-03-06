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

title: has_content-rating
linkTitle: has_content-rating

keywords: [content-rating]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- content_rating
- content-rating
- contentRating
- has_value_for_content_rating_stars
---

Predicate to describe the Quantity of CreativeWork.

Use it like this: 
- [ #has_/value/_for_content_rating_stars :: Rating, Text ] or 
- [ has_value_for_content_rating_stars :: Rating, Text ] 

Official rating of a piece of content&amp;#x2014;for example, &#x27;MPAA PG-13&#x27;.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_value_for_content_rating_stars )
( #has_/range :: Rating, Text )

