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

title: has_geo_location_geo_touches
linkTitle: has_geo_location_geo_touches

keywords: [geo_touches]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/geo

aliases:
- geo-touches
- geo_touches
- geoTouches
- has_geo_location_geo_touches
---

Predicate to describe the geo of GeospatialGeometry, Place.

Use it like this: 
- [ #has_/geo/_that_touches :: GeospatialGeometry, Place ] or 
- [ has_geo_geo_touches :: GeospatialGeometry, Place ] 

Represents spatial relations in which two geometries (or the places they represent) touch: &quot;they have at least one boundary point in common, but no interior points.&quot; (A symmetric relationship, as defined in &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/DE-9IM&quot;&gt;DE-9IM&lt;/a&gt;.)

Predicate describes that: 
[ #has_/domain  :: GeospatialGeometry, Place ]
( #has_/name :: has_geo_location_geo_touches )
( #has_/range :: GeospatialGeometry, Place )

