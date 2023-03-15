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

tags:
- schema.org/Predicate/geo

aliases:
- spatial
- spatial
- spatial
- has_geo_location_spatial
---

Predicate to describe the geo of CreativeWork.

Use it like this: 
- [ #has_/geo/_spatial :: Place ] or 
- [ has_geo_spatial :: Place ] 

The &quot;spatial&quot; property can be used in cases when more specific properties
(e.g. [[locationCreated]], [[spatialCoverage]], [[contentLocation]]) are not known to be appropriate.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_geo_location_spatial )
( #has_/range :: Place )

