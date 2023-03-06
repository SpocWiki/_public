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

title: has_geo_location_location_created
linkTitle: has_geo_location_location_created

keywords: [location_created]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- location-created
- location_created
- locationCreated
- has_geo_location_location_created
---

Predicate to describe the geo of CreativeWork.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_location_created :: Place ] or 
- [ has_geo_location_created :: Place ] 

The location where the CreativeWork was created, which may not be the same as the location depicted in the CreativeWork.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_geo_location_location_created )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

