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
title: has_toc_entry

linkTitle: has_toc_entry
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
- toc-entry
- toc_entry
- tocEntry
- has_toc_entry
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_toc_entry :: HyperTocEntry] or 
- [ has_toc_entry :: HyperTocEntry] 

Indicates a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/HyperTocEntry&quot;&gt;HyperTocEntry&lt;/a&gt; in a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/HyperToc&quot;&gt;HyperToc&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: HyperToc]
( #has_/name :: is_toc_entry)
( #has_/range :: HyperTocEntry)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: hasPart]

[ #has_/sub_properties :: ]

