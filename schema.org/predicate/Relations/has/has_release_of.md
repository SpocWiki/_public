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
title: has_release_of

linkTitle: has_release_of
keywords: [release, of]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- release-of
- release_of
- releaseOf
- has_release_of
---

Use it like this: 
- [ #has/_release_of :: MusicAlbum ] or 
- [ has_release_of :: MusicAlbum ] 

The album this is a release of.

Relation describes that: 
[ #has_/domain  :: MusicRelease ]
( #has_/name :: is_release_of )
( #has_/range :: MusicAlbum )

[ #is_/inverse_of  :: albumRelease ]

