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
title: has_competitor

linkTitle: has_competitor
keywords: [competitor]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- competitor
- competitor
- competitor
- has_competitor
---

Use it like this: 
- [ #has/_competitor :: Person, SportsTeam ] or 
- [ has_competitor :: Person, SportsTeam ] 

A competitor in a sports event.

Relation describes that: 
[ #has_/domain  :: SportsEvent ]
( #has_/name :: is_competitor )
( #has_/range :: Person, SportsTeam )

[ #has_/sub_properties :: [ awayTeam, homeTeam ] ]

