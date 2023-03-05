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
title: has_part_of_tv_series

linkTitle: has_part_of_tv_series
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: partOfSeries

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-tv-series
- part_of_tv_series
- partOfTVSeries
- has_part_of_tv_series
---

Use it like this: 
- [ #has/_part_of_tv_series :: TVSeries] or 
- [ has_part_of_tv_series :: TVSeries] 

The TV series to which this episode or season belongs.

Relation describes that: 
[ #has_/domain  :: TVClip, TVEpisode, TVSeason]
( #has_/name :: is_part_of_tv_series)
( #has_/range :: TVSeries)

[ #is_/sub_property_of  :: isPartOf]

