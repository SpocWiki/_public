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
title: has_price_type

linkTitle: has_price_type
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
- price-type
- price_type
- priceType
- has_price_type
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_price_type :: PriceTypeEnumeration, Text] or 
- [ has_price_type :: PriceTypeEnumeration, Text] 

Defines the type of a price specified for an offered product, for example a list price, a (temporary) sale price or a manufacturer suggested retail price. If multiple prices are specified for an offer the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/priceType&quot;&gt;priceType&lt;/a&gt; property can be used to identify the type of each such specified price. The value of priceType can be specified as a value from enumeration PriceTypeEnumeration or as a free form text string for price types that are not already predefined in PriceTypeEnumeration.

Relation describes that: 
[ #has_/domain  :: CompoundPriceSpecification, UnitPriceSpecification]
( #has_/name :: is_price_type)
( #has_/range :: PriceTypeEnumeration, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

