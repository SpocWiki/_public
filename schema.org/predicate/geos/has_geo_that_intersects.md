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

title: has_geo_location_geo_intersects
linkTitle: has_geo_location_geo_intersects

keywords: [geo_intersects]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- geo-intersects
- geo_intersects
- geoIntersects
- has_geo_location_geo_intersects
---

Predicate to describe the geo of GeospatialGeometry, Place.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_that_intersects :: GeospatialGeometry, Place ] or 
- [ has_geo_geo_intersects :: GeospatialGeometry, Place ] 

Represents spatial relations in which two geometries (or the places they represent) have at least one point in common. As defined in &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/DE-9IM&quot;&gt;DE-9IM&lt;/a&gt;.

Predicate describes that: 
[ #has_/domain  :: GeospatialGeometry, Place ]
( #has_/name :: has_geo_location_geo_intersects )
( #has_/range :: GeospatialGeometry, Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

