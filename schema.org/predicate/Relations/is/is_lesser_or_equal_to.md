---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: is_lesser_or_equal_to

linkTitle: is_lesser_or_equal_to
keywords: [lesser, or, equal]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- lesser-or-equal
- lesser_or_equal
- lesserOrEqual
- is_lesser_or_equal_to
---

Use it like this: 
- [ #is/_lesser_or_equal_to :: QualitativeValue ] or 
- [ is_lesser_or_equal_to :: QualitativeValue ] 

This ordering relation for qualitative values indicates that the subject is lesser than or equal to the object.

Relation describes that: 
[ #has_/domain  :: QualitativeValue ]
( #has_/name :: is_lesser_or_equal_to )
( #has_/range :: QualitativeValue )

[[../is_inverse_of]]

[ #is_/inverse_of :: [[is_greater_or_equal_to]]] 

[ #is_/complement_of  :: [[is_greater_than]]] 
