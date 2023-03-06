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

title: has_geo_location_geo
linkTitle: has_geo_location_geo

keywords: [geo]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/geo

aliases:
- geo
- geo
- geo
- has_geo_location_geo
---

Predicate to describe the geo of Place.

Use it like this: 
- [ #has_/geo/_place :: GeoCoordinates, GeoShape ] or 
- [ has_geo_geo :: GeoCoordinates, GeoShape ] 

The geo coordinates of the place.

Predicate describes that: 
[ #has_/domain  :: Place ]
( #has_/name :: has_geo_location_geo )
( #has_/range :: GeoCoordinates, GeoShape )

