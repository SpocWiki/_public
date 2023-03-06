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

title: has_geo_location_geo_midpoint
linkTitle: has_geo_location_geo_midpoint

keywords: [geo_midpoint]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/geo

aliases:
- geo-midpoint
- geo_midpoint
- geoMidpoint
- has_geo_location_geo_midpoint
---

Predicate to describe the geo of GeoCircle.

Use it like this: 
- [ #has_/geo/_midpoint :: GeoCoordinates ] or 
- [ has_geo_geo_midpoint :: GeoCoordinates ] 

Indicates the GeoCoordinates at the centre of a GeoShape, e.g. GeoCircle.

Predicate describes that: 
[ #has_/domain  :: GeoCircle ]
( #has_/name :: has_geo_location_geo_midpoint )
( #has_/range :: GeoCoordinates )

