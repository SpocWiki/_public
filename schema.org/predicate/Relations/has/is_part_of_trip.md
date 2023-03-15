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
title: is_part_of_trip

linkTitle: is_part_of_trip
keywords: [part, of, trip]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-trip
- part_of_trip
- partOfTrip
- is_part_of_trip
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #is/_part_of_trip :: Trip ] or 
- [ is_part_of_trip :: Trip ] 

Identifies that this [[Trip]] is a subTrip of another Trip.  For example Day 1, Day 2, etc. of a multi-day trip.

Relation describes that: 
[ #has_/domain  :: Trip ]
( #has_/name :: is_part_of_trip )
( #has_/range :: Trip )

[ #is_/inverse_of  :: subTrip ]

