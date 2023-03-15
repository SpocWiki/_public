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

title: has_latitude
linkTitle: has_latitude

keywords: [latitude]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- latitude
- latitude
- latitude
- has_value_for_latitude
---

Predicate to describe the Quantity of GeoCoordinates, Place.

Use it like this: 
- [ #has_/value/_for_latitude :: Number, Text ] or 
- [ has_value_for_latitude :: Number, Text ] 

The latitude of a location. For example &lt;code&gt;37.42242&lt;/code&gt; (&lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/World_Geodetic_System&quot;&gt;WGS 84]]).

Predicate describes that: 
[ #has_/domain  :: GeoCoordinates, Place ]
( #has_/name :: has_value_for_latitude )
( #has_/range :: Number, Text )

