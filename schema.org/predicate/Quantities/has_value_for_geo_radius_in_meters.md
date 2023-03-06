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

title: has_geo-radius
linkTitle: has_geo-radius

keywords: [geo-radius]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- geo_radius
- geo-radius
- geoRadius
- has_value_for_geo_radius_in_meters
---

Predicate to describe the Quantity of GeoCircle.

Use it like this: 
- [ #has_/value/_for_geo_radius_in_meters :: Distance, Number, Text ] or 
- [ has_value_for_geo_radius_in_meters :: Distance, Number, Text ] 

Indicates the approximate radius of a GeoCircle (metres unless indicated otherwise via Distance notation).

Predicate describes that: 
[ #has_/domain  :: GeoCircle ]
( #has_/name :: has_value_for_geo_radius_in_meters )
( #has_/range :: Distance, Number, Text )

