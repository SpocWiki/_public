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

title: has_geo_location_pickup_location
linkTitle: has_geo_location_pickup_location

keywords: [pickup_location]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- pickup-location
- pickup_location
- pickupLocation
- has_geo_location_pickup_location
---

Predicate to describe the geo of RentalCarReservation, TaxiReservation.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_pickup_location :: Place ] or 
- [ has_geo_pickup_location :: Place ] 

Where a taxi will pick up a passenger or a rental car can be picked up.

Predicate describes that: 
[ #has_/domain  :: RentalCarReservation, TaxiReservation ]
( #has_/name :: has_geo_location_pickup_location )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

