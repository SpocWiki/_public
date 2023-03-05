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
title: has_album_release

linkTitle: has_album_release
keywords: [album, release]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- album-release
- album_release
- albumRelease
- has_album_release
---

Use it like this: 
- [ #has/_album_release :: MusicRelease ] or 
- [ has_album_release :: MusicRelease ] 

A release of this album.

Relation describes that: 
[ #has_/domain  :: MusicAlbum ]
( #has_/name :: is_album_release )
( #has_/range :: MusicRelease )

[ #is_/inverse_of  :: releaseOf ]

