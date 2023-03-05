---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_address_country

linkTitle: has_address_country
keywords: [address, country]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- address-country
- address_country
- addressCountry
- has_address_country
---

Use it like this: 
- [ #has/_address_country :: Country, Text ] or 
- [ has_address_country :: Country, Text ] 

The country. For example, USA. You can also provide the two-letter &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/ISO_3166-1&quot;&gt;ISO 3166-1 alpha-2 country code&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: DefinedRegion, GeoCoordinates, GeoShape, PostalAddress ]
( #has_/name :: is_address_country )
( #has_/range :: Country, Text )

