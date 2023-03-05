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
title: has_image

linkTitle: has_image
keywords: [image]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- image
- image
- image
- has_image
---

Use it like this: 
- [ #has/_image :: ImageObject, URL ] or 
- [ has_image :: ImageObject, URL ] 

An image of the item. This can be a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/URL&quot;&gt;URL&lt;/a&gt; or a fully described &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ImageObject&quot;&gt;ImageObject&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Thing ]
( #has_/name :: is_image )
( #has_/range :: ImageObject, URL )

[ #has_/sub_properties :: [ layoutImage, logo, photo ] ]

