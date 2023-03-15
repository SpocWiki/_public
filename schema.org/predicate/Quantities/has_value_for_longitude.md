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

title: has_longitude
linkTitle: has_longitude

keywords: [longitude]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- longitude
- longitude
- longitude
- has_value_for_longitude
---

Predicate to describe the Quantity of GeoCoordinates, Place.

Use it like this: 
- [ #has_/value/_for_longitude :: Number, Text ] or 
- [ has_value_for_longitude :: Number, Text ] 

The longitude of a location. For example &lt;code&gt;-122.08585&lt;/code&gt; (&lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/World_Geodetic_System&quot;&gt;WGS 84&lt;/a&gt;).

Predicate describes that: 
[ #has_/domain  :: GeoCoordinates, Place ]
( #has_/name :: has_value_for_longitude )
( #has_/range :: Number, Text )

