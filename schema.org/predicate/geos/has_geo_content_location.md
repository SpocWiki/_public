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

title: has_geo_location_content_location
linkTitle: has_geo_location_content_location

keywords: [content_location]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/geo

aliases:
- content-location
- content_location
- contentLocation
- has_geo_location_content_location
---

Predicate to describe the geo of CreativeWork.

Use it like this: 
- [ #has_/geo/_content_location :: Place ] or 
- [ has_geo_content_location :: Place ] 

The location depicted or described in the content. For example, the location in a photograph or painting.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_geo_location_content_location )
( #has_/range :: Place )

[ #has_/sub_properties :: [ spatialCoverage ] ]

