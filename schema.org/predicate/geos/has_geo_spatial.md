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

title: has_geo_location_spatial
linkTitle: has_geo_location_spatial

keywords: [spatial]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- spatial
- spatial
- spatial
- has_geo_location_spatial
---

Predicate to describe the geo of CreativeWork.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_spatial :: Place ] or 
- [ has_geo_spatial :: Place ] 

The &quot;spatial&quot; property can be used in cases when more specific properties
(e.g. &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/locationCreated&quot;&gt;locationCreated&lt;/a&gt;, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/spatialCoverage&quot;&gt;spatialCoverage&lt;/a&gt;, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/contentLocation&quot;&gt;contentLocation&lt;/a&gt;) are not known to be appropriate.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_geo_location_spatial )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

