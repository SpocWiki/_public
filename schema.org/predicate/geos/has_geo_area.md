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

title: has_geo_location_area
linkTitle: has_geo_location_area

keywords: [area]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: serviceArea

tags:
- schema.org/Predicate/geo

aliases:
- area
- area
- area
- has_geo_location_area
---

Predicate to describe the geo of BroadcastService.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_area :: Place ] or 
- [ has_geo_area :: Place ] 

The area within which users can expect to reach the broadcast service.

Predicate describes that: 
[ #has_/domain  :: BroadcastService ]
( #has_/name :: has_geo_location_area )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

