---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Quantity
publish: true

# Hugo Tags
type: Predi_Quantity

title: has_elevation
linkTitle: has_elevation

keywords: [elevation]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- elevation_in_meters
- elevation
- elevation
- has_value_for_elevation
---

Predicate to describe the Quantity of GeoCoordinates, GeoShape.

Use it like this: 
- [ #has_/value/_for_elevation :: Number, Text ] or 
- [ has_value_for_elevation :: Number, Text ] 

The elevation of a location (&lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/World_Geodetic_System&quot;&gt;WGS 84&lt;/a&gt;). Values may be of the form &#x27;NUMBER UNIT_OF_MEASUREMENT&#x27; (e.g., &#x27;1,000 m&#x27;, &#x27;3,200 ft&#x27;) while numbers alone should be assumed to be a value in meters.

Predicate describes that: 
[ #has_/domain  :: GeoCoordinates, GeoShape ]
( #has_/name :: has_value_for_elevation )
( #has_/range :: Number, Text )

