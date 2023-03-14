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
title: is_applicable_in_country

linkTitle: is_applicable_in_country
keywords: [applicable, country]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- applicable-country
- applicable_country
- applicableCountry
- is_applicable_in_country
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_applicable_country :: Country, Text ] or 
- [ is_applicable_in_country :: Country, Text ] 

A country where a particular merchant return policy applies to, for example the two-letter ISO 3166-1 alpha-2 country code.

Relation describes that: 
[ #has_/domain  :: MerchantReturnPolicy ]
( #has_/name :: is_applicable_in_country )
( #has_/range :: Country, Text )

