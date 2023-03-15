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
title: is_part_of_season

linkTitle: is_part_of_season
keywords: [part, of, season]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-season
- part_of_season
- partOfSeason
- is_part_of_season
---

Use it like this: 
- [ #is/_part_of_season :: CreativeWorkSeason ] or 
- [ is_part_of_season :: CreativeWorkSeason ] 

The season to which this episode belongs.

Relation describes that: 
[ #has_/domain  :: Clip, Episode ]
( #has_/name :: is_part_of_season )
( #has_/range :: CreativeWorkSeason )

[ #is_/sub_property_of  :: isPartOf ]

