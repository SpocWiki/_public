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
title: has_applicable_country

linkTitle: has_applicable_country
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- applicable-country
- applicable_country
- applicableCountry
- has_applicable_country
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_applicable_country :: Country, Text] or 
- [ has_applicable_country :: Country, Text] 

A country where a particular merchant return policy applies to, for example the two-letter ISO 3166-1 alpha-2 country code.

Relation describes that: 
[ #has_/domain  :: MerchantReturnPolicy]
( #has_/name :: is_applicable_country)
( #has_/range :: Country, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

