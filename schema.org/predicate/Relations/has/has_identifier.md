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
title: has_identifier

linkTitle: has_identifier
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
- identifier
- identifier
- identifier
- has_identifier
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_identifier :: PropertyValue, Text, URL] or 
- [ has_identifier :: PropertyValue, Text, URL] 

The identifier property represents any kind of identifier for any kind of &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Thing&quot;&gt;Thing&lt;/a&gt;, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See &lt;a href&#x3D;&quot;/docs/datamodel.html#identifierBg&quot;&gt;background notes&lt;/a&gt; for more details.

Relation describes that: 
[ #has_/domain  :: Thing]
( #has_/name :: is_identifier)
( #has_/range :: PropertyValue, Text, URL)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: accountId, asin, callSign, confirmationNumber, duns, editEIDR, flightNumber, globalLocationNumber, gtin, gtin12, gtin13, gtin14, gtin8, isbn, issn, legislationIdentifier, leiCode, nsn, orderNumber, productID, serialNumber, sku, taxID, titleEIDR]

