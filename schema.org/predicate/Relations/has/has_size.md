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
title: has_size

linkTitle: has_size
keywords: [size]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- size
- size
- size
- has_size
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_size :: DefinedTerm, QuantitativeValue, SizeSpecification, Text ] or 
- [ has_size :: DefinedTerm, QuantitativeValue, SizeSpecification, Text ] 

A standardized size of a product or creative work, specified either through a simple textual string (for example 'XL', '32Wx34L'), a  QuantitativeValue with a unitCode, or a comprehensive and structured &lt;a class="localLink" href="/SizeSpecification"&gt;SizeSpecification&lt;/a&gt;; in other cases, the &lt;a class="localLink" href="/width"&gt;width&lt;/a&gt;, &lt;a class="localLink" href="/height"&gt;height&lt;/a&gt;, &lt;a class="localLink" href="/depth"&gt;depth&lt;/a&gt; and &lt;a class="localLink" href="/weight"&gt;weight&lt;/a&gt; properties may be more applicable.

Relation describes that: 
[ #has_/domain  :: CreativeWork, Product ]
( #has_/name :: is_size )
( #has_/range :: DefinedTerm, QuantitativeValue, SizeSpecification, Text )

