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
title: has_variant

linkTitle: has_variant
keywords: [variant]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- has-variant
- variant
- hasVariant
- has_variant
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_variant :: Product ] or 
- [ has_variant :: Product ] 

Indicates a &lt;a class="localLink" href="/Product"&gt;Product&lt;/a&gt; that is a member of this &lt;a class="localLink" href="/ProductGroup"&gt;ProductGroup&lt;/a&gt; (or &lt;a class="localLink" href="/ProductModel"&gt;ProductModel&lt;/a&gt;).

Relation describes that: 
[ #has_/domain  :: ProductGroup ]
( #has_/name :: is_variant )
( #has_/range :: Product )

[ #is_/inverse_of  :: isVariantOf ]

