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
title: has_home_team

linkTitle: has_home_team
keywords: [home, team]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- home-team
- home_team
- homeTeam
- has_home_team
---

Use it like this: 
- [ #has/_home_team :: Person, SportsTeam ] or 
- [ has_home_team :: Person, SportsTeam ] 

The home team in a sports event.

Relation describes that: 
[ #has_/domain  :: SportsEvent ]
( #has_/name :: has_home_team )
( #has_/range :: Person, SportsTeam )

[ #is_/sub_property_of  :: competitor ]

