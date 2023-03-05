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
title: has_credited_to

linkTitle: has_credited_to
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- credited-to
- credited_to
- creditedTo
- has_credited_to
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_credited_to :: Organization, Person] or 
- [ has_credited_to :: Organization, Person] 

The group the release is credited to if different than the byArtist. For example, Red and Blue is credited to &quot;Stefani Germanotta Band&quot;, but by Lady Gaga.

Relation describes that: 
[ #has_/domain  :: MusicRelease]
( #has_/name :: is_credited_to)
( #has_/range :: Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

