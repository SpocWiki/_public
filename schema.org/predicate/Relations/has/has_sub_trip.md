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
title: has_sub_trip

linkTitle: has_sub_trip
keywords: [sub, trip]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- sub-trip
- sub_trip
- subTrip
- has_sub_trip
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_sub_trip :: Trip ] or 
- [ has_sub_trip :: Trip ] 

Identifies a &lt;a class="localLink" href="/Trip"&gt;Trip&lt;/a&gt; that is a subTrip of this Trip.  For example Day 1, Day 2, etc. of a multi-day trip.

Relation describes that: 
[ #has_/domain  :: Trip ]
( #has_/name :: is_sub_trip )
( #has_/range :: Trip )

[ #is_/inverse_of  :: partOfTrip ]

