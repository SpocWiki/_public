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
title: has_part_of_trip

linkTitle: has_part_of_trip
keywords: [part, of, trip]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-trip
- part_of_trip
- partOfTrip
- has_part_of_trip
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_part_of_trip :: Trip ] or 
- [ has_part_of_trip :: Trip ] 

Identifies that this &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Trip&quot;&gt;Trip&lt;/a&gt; is a subTrip of another Trip.  For example Day 1, Day 2, etc. of a multi-day trip.

Relation describes that: 
[ #has_/domain  :: Trip ]
( #has_/name :: is_part_of_trip )
( #has_/range :: Trip )

[ #is_/inverse_of  :: subTrip ]

