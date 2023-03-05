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
title: is_varying_by

linkTitle: is_varying_by
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- varies-by
- varying_by
- variesBy
- is_varying_by
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #is/_varying_by :: DefinedTerm, Text] or 
- [ is_varying_by :: DefinedTerm, Text] 

Indicates the property or properties by which the variants in a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ProductGroup&quot;&gt;ProductGroup&lt;/a&gt; vary, e.g. their size, color etc. Schema.org properties can be referenced by their short name e.g. &quot;color&quot;; terms defined elsewhere can be referenced with their URIs.

Relation describes that: 
[ #has_/domain  :: ProductGroup]
( #has_/name :: is_varying_by)
( #has_/range :: DefinedTerm, Text)

