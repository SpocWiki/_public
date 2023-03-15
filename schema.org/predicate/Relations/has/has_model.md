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
title: has_model

linkTitle: has_model
keywords: [model]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- model
- model
- model
- has_model
---

Use it like this: 
- [ #has/_model :: ProductModel, Text ] or 
- [ has_model :: ProductModel, Text ] 

The model of the product. 

Use with the URL of a ProductModel or a textual representation of the model identifier. 

The URL of the ProductModel can be from an external source. 

It is recommended to additionally provide strong product identifiers 
via the gtin8/gtin13/gtin14 and mpn properties.

Relation describes that: 
[ #has_/domain  :: Product ]
( #has_/name :: has_model )
( #has_/range :: ProductModel, Text )

