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
title: has_target_product

linkTitle: has_target_product
keywords: [target, product]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- target-product
- target_product
- targetProduct
- has_target_product
---

Use it like this: 
- [ #has/_target_product :: SoftwareApplication ] or 
- [ has_target_product :: SoftwareApplication ] 

Target Operating System / Product to which the code applies.  If applies to several versions, just the product name can be used.

Relation describes that: 
[ #has_/domain  :: SoftwareSourceCode ]
( #has_/name :: is_target_product )
( #has_/range :: SoftwareApplication )

