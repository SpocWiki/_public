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
title: has_product_supported

linkTitle: has_product_supported
keywords: [product, supported]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- product-supported
- product_supported
- productSupported
- has_product_supported
---

Use it like this: 
- [ #has/_product_supported :: Product, Text ] or 
- [ has_product_supported :: Product, Text ] 

The product or service this support contact point is related to (such as product support for a particular product line). This can be a specific product or product line (e.g. &quot;iPhone&quot;) or a general category of products or services (e.g. &quot;smartphones&quot;).

Relation describes that: 
[ #has_/domain  :: ContactPoint ]
( #has_/name :: is_product_supported )
( #has_/range :: Product, Text )

