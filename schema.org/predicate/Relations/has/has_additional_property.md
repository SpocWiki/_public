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
title: has_additional_property

linkTitle: has_additional_property
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
- additional-property
- additional_property
- additionalProperty
- has_additional_property
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_additional_property :: PropertyValue] or 
- [ has_additional_property :: PropertyValue] 

A property-value pair representing an additional characteristic of the entity, e.g. a product feature or another characteristic for which there is no matching property in schema.org.&lt;br/&gt;&lt;br/&gt;

Note: Publishers should be aware that applications designed to use specific schema.org properties (e.g. width, color, gtin13, ...) will typically expect such data to be provided using those properties, rather than using the generic property/value mechanism.

Relation describes that: 
[ #has_/domain  :: MerchantReturnPolicy, Place, Product, QualitativeValue, QuantitativeValue]
( #has_/name :: is_additional_property)
( #has_/range :: PropertyValue)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

