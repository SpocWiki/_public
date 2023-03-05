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
title: has_positive_notes

linkTitle: has_positive_notes
keywords: [positive, notes]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- positive-notes
- positive_notes
- positiveNotes
- has_positive_notes
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_positive_notes :: ItemList, ListItem, Text, WebContent ] or 
- [ has_positive_notes :: ItemList, ListItem, Text, WebContent ] 

Provides positive considerations regarding something, for example product highlights or (alongside &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/negativeNotes&quot;&gt;negativeNotes&lt;/a&gt;) pro/con lists for reviews.&lt;br/&gt;&lt;br/&gt;

In the case of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Review&quot;&gt;Review&lt;/a&gt;, the property describes the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/itemReviewed&quot;&gt;itemReviewed&lt;/a&gt; from the perspective of the review; in the case of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Product&quot;&gt;Product&lt;/a&gt;, the product itself is being described.&lt;br/&gt;&lt;br/&gt;

The property values can be expressed either as unstructured text (repeated as necessary), or if ordered, as a list (in which case the most positive is at the beginning of the list).

Relation describes that: 
[ #has_/domain  :: Product, Review ]
( #has_/name :: is_positive_notes )
( #has_/range :: ItemList, ListItem, Text, WebContent )

