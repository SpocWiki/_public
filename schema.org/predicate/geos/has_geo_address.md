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

title: has_geo_location_address
linkTitle: has_geo_location_address

keywords: [address]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- address
- address
- address
- has_geo_location_address
---

Predicate to describe the geo of GeoCoordinates, GeoShape, Organization, Person, Place.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_address :: PostalAddress, Text ] or 
- [ has_geo_address :: PostalAddress, Text ] 

Physical address of the item.

Predicate describes that: 
[ #has_/domain  :: GeoCoordinates, GeoShape, Organization, Person, Place ]
( #has_/name :: has_geo_location_address )
( #has_/range :: PostalAddress, Text )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

