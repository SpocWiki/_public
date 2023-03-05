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
- size
- size
- size
- has_size
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_size :: DefinedTerm, QuantitativeValue, SizeSpecification, Text] or 
- [ has_size :: DefinedTerm, QuantitativeValue, SizeSpecification, Text] 

A standardized size of a product or creative work, specified either through a simple textual string (for example &#x27;XL&#x27;, &#x27;32Wx34L&#x27;), a  QuantitativeValue with a unitCode, or a comprehensive and structured &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/SizeSpecification&quot;&gt;SizeSpecification&lt;/a&gt;; in other cases, the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/width&quot;&gt;width&lt;/a&gt;, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/height&quot;&gt;height&lt;/a&gt;, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/depth&quot;&gt;depth&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/weight&quot;&gt;weight&lt;/a&gt; properties may be more applicable.

Relation describes that: 
[ #has_/domain  :: CreativeWork, Product]
( #has_/name :: is_size)
( #has_/range :: DefinedTerm, QuantitativeValue, SizeSpecification, Text)

