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

title: has_geo_location_regions_allowed
linkTitle: has_geo_location_regions_allowed

keywords: [regions_allowed]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- regions-allowed
- regions_allowed
- regionsAllowed
- has_geo_location_regions_allowed
---

Predicate to describe the geo of MediaObject.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_regions_allowed :: Place ] or 
- [ has_geo_regions_allowed :: Place ] 

The regions where the media is allowed. If not specified, then it&#x27;s assumed to be allowed everywhere. Specify the countries in &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/ISO_3166&quot;&gt;ISO 3166 format&lt;/a&gt;.

Predicate describes that: 
[ #has_/domain  :: MediaObject ]
( #has_/name :: has_geo_location_regions_allowed )
( #has_/range :: Place )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

