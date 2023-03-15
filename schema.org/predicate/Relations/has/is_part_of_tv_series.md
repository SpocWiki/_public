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
title: is_part_of_tv_series

linkTitle: is_part_of_tv_series
keywords: [part, of, tv, series]
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: partOfSeries

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-tv-series
- part_of_tv_series
- partOfTVSeries
- is_part_of_tv_series
---

Use it like this: 
- [ #is/_part_of_tv_series :: TVSeries ] or 
- [ is_part_of_tv_series :: TVSeries ] 

The TV series to which this episode or season belongs.

Relation describes that: 
[ #has_/domain  :: TVClip, TVEpisode, TVSeason ]
( #has_/name :: is_part_of_tv_series )
( #has_/range :: [[../../../Type/is_a_/creative_work/tv_series|TV-Series]] )

[ #is_/sub_property_of  :: [[../is_part_of]] ]

