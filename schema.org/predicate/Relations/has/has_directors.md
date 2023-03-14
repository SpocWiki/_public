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
title: has_directors

linkTitle: has_directors
keywords: [directors]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- directors
- directors
- directors
- has_directors
---

[ superseded_by :: [[director]] ]

Use it like this: 
- [ #has/_director :: Person ] or 
- [ has_director :: Person ] 

A director of e.g. TV, radio, movie, video games etc. content. Directors can be associated with individual items or with a series, episode, clip.

Relation describes that: 
[ #has_/domain  :: Clip, Episode, Movie, MovieSeries, RadioSeries, TVSeries, VideoGame, VideoGameSeries, VideoObject ]
( #has_/name :: has_directors )
( #has_/range :: Person )

