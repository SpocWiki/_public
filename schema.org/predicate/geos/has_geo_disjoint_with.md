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

title: has_geo_location_geo_disjoint
linkTitle: has_geo_location_geo_disjoint

keywords: [geo_disjoint]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/geo

aliases:
- geo-disjoint
- geo_disjoint
- geoDisjoint
- has_geo_location_geo_disjoint
---

Predicate to describe the geo of GeospatialGeometry, Place.

Use it like this: 
- [ #has_/geo/_disjoint_with :: GeospatialGeometry, Place ] or 
- [ has_geo_geo_disjoint :: GeospatialGeometry, Place ] 

Represents spatial relations in which two geometries (or the places they represent) are topologically disjoint: &quot;they have no point in common. They form a set of disconnected geometries.&quot; (A symmetric relationship, as defined in &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/DE-9IM&quot;&gt;DE-9IM]].)

Predicate describes that: 
[ #has_/domain  :: GeospatialGeometry, Place ]
( #has_/name :: has_geo_location_geo_disjoint )
( #has_/range :: GeospatialGeometry, Place )

