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

title: has_geo_location_service_location
linkTitle: has_geo_location_service_location

keywords: [service_location]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- service-location
- service_location
- serviceLocation
- has_geo_location_service_location
---

Predicate to describe the geo of ServiceChannel.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_service_location :: Place ] or 
- [ has_geo_service_location :: Place ] 

The location (e.g. civic structure, local business, etc.) where a person can go to access the service.

Predicate describes that: 
[ #has_/domain  :: ServiceChannel ]
( #has_/name :: has_geo_location_service_location )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

