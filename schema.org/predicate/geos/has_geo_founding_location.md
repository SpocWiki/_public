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

title: has_geo_location_founding_location
linkTitle: has_geo_location_founding_location

keywords: [founding_location]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/geo

aliases:
- founding-location
- founding_location
- foundingLocation
- has_geo_location_founding_location
---

Predicate to describe the geo of Organization.

Use it like this: 
- [ #has_/geo/_founding_location :: Place ] or 
- [ has_geo_founding_location :: Place ] 

The place where the Organization was founded.

Predicate describes that: 
[ #has_/domain  :: Organization ]
( #has_/name :: has_geo_location_founding_location )
( #has_/range :: Place )

