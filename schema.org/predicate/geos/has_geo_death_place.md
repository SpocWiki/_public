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

title: has_geo_location_death_place
linkTitle: has_geo_location_death_place

keywords: [death_place]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- death-place
- death_place
- deathPlace
- has_geo_location_death_place
---

Predicate to describe the geo of Person.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_death_place :: Place ] or 
- [ has_geo_death_place :: Place ] 

The place where the person died.

Predicate describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_geo_location_death_place )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

