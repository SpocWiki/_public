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
title: has_correction

linkTitle: has_correction
keywords: [correction]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- correction
- correction
- correction
- has_correction
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_correction :: CorrectionComment, Text, URL ] or 
- [ has_correction :: CorrectionComment, Text, URL ] 

Indicates a correction to a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CreativeWork&quot;&gt;CreativeWork&lt;/a&gt;, either via a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CorrectionComment&quot;&gt;CorrectionComment&lt;/a&gt;, textually or in another document.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_correction )
( #has_/range :: CorrectionComment, Text, URL )

