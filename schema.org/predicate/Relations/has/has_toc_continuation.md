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
title: has_toc_continuation

linkTitle: has_toc_continuation
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
- toc-continuation
- toc_continuation
- tocContinuation
- has_toc_continuation
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_toc_continuation :: HyperTocEntry] or 
- [ has_toc_continuation :: HyperTocEntry] 

A &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/HyperTocEntry&quot;&gt;HyperTocEntry&lt;/a&gt; can have a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/tocContinuation&quot;&gt;tocContinuation&lt;/a&gt; indicated, which is another &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/HyperTocEntry&quot;&gt;HyperTocEntry&lt;/a&gt; that would be the default next item to play or render.

Relation describes that: 
[ #has_/domain  :: HyperTocEntry]
( #has_/name :: is_toc_continuation)
( #has_/range :: HyperTocEntry)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

