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

title: has_geo_location_contained_in_place
linkTitle: has_geo_location_contained_in_place

keywords: [contained_in_place]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: containedIn

tags:
- schema.org/Predicate/geo

aliases:
- contained-in-place
- contained_in_place
- containedInPlace
- has_geo_location_contained_in_place
---

Predicate to describe the geo of Place.

Use it like this: 
- [ #has_/geo/_contained_in_place :: Place ] or 
- [ has_geo_contained_in_place :: Place ] 

The basic containment relation between a place and one that contains it.

Predicate describes that: 
[ #has_/domain  :: Place ]
( #has_/name :: has_geo_location_contained_in_place )
( #has_/range :: Place )

[ #is_/inverse_of  :: containsPlace ]

