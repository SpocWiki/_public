---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate geo
publish: true

# Hugo Tags
type: Pred_geo

title: has_geo_location_game_location
linkTitle: has_geo_location_game_location

keywords: [game_location]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- game-location
- game_location
- gameLocation
- has_geo_location_game_location
---

Predicate to describe the geo of Game, VideoGameSeries.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_game_location :: Place, PostalAddress, URL ] or 
- [ has_geo_game_location :: Place, PostalAddress, URL ] 

Real or fictional location of the game (or part of game).

Predicate describes that: 
[ #has_/domain  :: Game, VideoGameSeries ]
( #has_/name :: has_geo_location_game_location )
( #has_/range :: Place, PostalAddress, URL )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

