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

title: has_geo_location_dropoff_location
linkTitle: has_geo_location_dropoff_location

keywords: [dropoff_location]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- dropoff-location
- dropoff_location
- dropoffLocation
- has_geo_location_dropoff_location
---

Predicate to describe the geo of RentalCarReservation.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_dropoff_location :: Place ] or 
- [ has_geo_dropoff_location :: Place ] 

Where a rental car can be dropped off.

Predicate describes that: 
[ #has_/domain  :: RentalCarReservation ]
( #has_/name :: has_geo_location_dropoff_location )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

