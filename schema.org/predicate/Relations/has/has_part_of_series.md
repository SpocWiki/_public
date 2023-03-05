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
title: has_part_of_series

linkTitle: has_part_of_series
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: partOfTVSeries
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-series
- part_of_series
- partOfSeries
- has_part_of_series
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_part_of_series :: CreativeWorkSeries] or 
- [ has_part_of_series :: CreativeWorkSeries] 

The series to which this episode or season belongs.

Relation describes that: 
[ #has_/domain  :: Clip, CreativeWorkSeason, Episode]
( #has_/name :: is_part_of_series)
( #has_/range :: CreativeWorkSeries)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: isPartOf]

[ #has_/sub_properties :: ]
