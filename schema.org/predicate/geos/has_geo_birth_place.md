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

title: has_geo_location_birth_place
linkTitle: has_geo_location_birth_place

keywords: [birth_place]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- birth-place
- birth_place
- birthPlace
- has_geo_location_birth_place
---

Predicate to describe the geo of Person.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_birth_place :: Place ] or 
- [ has_geo_birth_place :: Place ] 

The place where the person was born.

Predicate describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_geo_location_birth_place )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

