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
title: has_contains_season

linkTitle: has_contains_season
keywords: [contains, season]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: season

tags:
- schema.org/Predicate/Relation

aliases:
- contains-season
- contains_season
- containsSeason
- has_contains_season
---

Use it like this: 
- [ #has/_contains_season :: CreativeWorkSeason ] or 
- [ has_contains_season :: CreativeWorkSeason ] 

A season that is part of the media series.

Relation describes that: 
[ #has_/domain  :: RadioSeries, TVSeries, VideoGameSeries ]
( #has_/name :: is_contains_season )
( #has_/range :: CreativeWorkSeason )

[ #is_/sub_property_of  :: hasPart ]

