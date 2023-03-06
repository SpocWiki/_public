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
keywords: [toc, entry]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- toc-entry
- toc_entry
- tocEntry
- has_toc_entry
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_toc_entry :: HyperTocEntry ] or 
- [ has_toc_entry :: HyperTocEntry ] 

Indicates a &lt;a class="localLink" href="/HyperTocEntry"&gt;HyperTocEntry&lt;/a&gt; in a &lt;a class="localLink" href="/HyperToc"&gt;HyperToc&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: HyperToc ]
( #has_/name :: is_toc_entry )
( #has_/range :: HyperTocEntry )

[ #is_/sub_property_of  :: hasPart ]

