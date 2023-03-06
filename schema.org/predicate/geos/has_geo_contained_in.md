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

title: has_geo_location_contained_in
linkTitle: has_geo_location_contained_in

keywords: [contained_in]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: containedInPlace

tags:
- schema.org/Predicate/geo

aliases:
- contained-in
- contained_in
- containedIn
- has_geo_location_contained_in
---

Predicate to describe the geo of Place.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_contained_in :: Place ] or 
- [ has_geo_contained_in :: Place ] 

The basic containment relation between a place and one that contains it.

Predicate describes that: 
[ #has_/domain  :: Place ]
( #has_/name :: has_geo_location_contained_in )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

