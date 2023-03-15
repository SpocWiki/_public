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
title: has_negative_notes

linkTitle: has_negative_notes
keywords: [negative, notes]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- negative-notes
- negative_notes
- negativeNotes
- has_negative_notes
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_negative_notes :: ItemList, ListItem, Text, WebContent ] or 
- [ has_negative_notes :: ItemList, ListItem, Text, WebContent ] 

Provides negative considerations regarding something, most typically in pro/con lists for reviews (alongside [[positiveNotes]]). For symmetry &lt;br/&gt;&lt;br/&gt;

In the case of a [[Review]], the property describes the [[itemReviewed]] from the perspective of the review; in the case of a [[Product]], the product itself is being described. Since product descriptions 
tend to emphasise positive claims, it may be relatively unusual to find [[negativeNotes]] used in this way. Nevertheless for the sake of symmetry, [[negativeNotes]] can be used on [[Product]].&lt;br/&gt;&lt;br/&gt;

The property values can be expressed either as unstructured text (repeated as necessary), or if ordered, as a list (in which case the most negative is at the beginning of the list).

Relation describes that: 
[ #has_/domain  :: Product, Review ]
( #has_/name :: is_negative_notes )
( #has_/range :: ItemList, ListItem, Text, WebContent )

