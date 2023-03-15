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
title: has_music_by

linkTitle: has_music_by
keywords: [music, by]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- music-by
- music_by
- musicBy
- has_music_by
---

Use it like this: 
- [ #has/_music_by :: MusicGroup, Person ] or 
- [ has_music_by :: MusicGroup, Person ] 

The composer of the soundtrack.

Relation describes that: 
[ #has_/domain  :: Clip, Episode, Movie, MovieSeries, RadioSeries, TVSeries, VideoGame, VideoGameSeries, VideoObject ]
( #has_/name :: has_music_by )
( #has_/range :: MusicGroup, Person )

