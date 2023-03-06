---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate geo
publish: true

# Hugo Tags
type: Pred_geo

title: has_geo_location_contains_place
linkTitle: has_geo_location_contains_place

keywords: [contains_place]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/geo

aliases:
- contains-place
- contains_place
- containsPlace
- has_geo_location_contains_place
---

Predicate to describe the geo of Place.

Use it like this: 
- [ #has_/geo/_containing_place :: Place ] or 
- [ has_geo_contains_place :: Place ] 

The basic containment relation between a place and another that it contains.

Predicate describes that: 
[ #has_/domain  :: Place ]
( #has_/name :: has_geo_location_contains_place )
( #has_/range :: Place )

[ #is_/inverse_of  :: containedInPlace ]

