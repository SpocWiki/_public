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
title: has_departure_boat_terminal

linkTitle: has_departure_boat_terminal
keywords: [departure, boat, terminal]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- departure-boat-terminal
- departure_boat_terminal
- departureBoatTerminal
- has_departure_boat_terminal
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_departure_boat_terminal :: BoatTerminal ] or 
- [ has_departure_boat_terminal :: BoatTerminal ] 

The terminal or port from which the boat departs.

Relation describes that: 
[ #has_/domain  :: BoatTrip ]
( #has_/name :: has_departure_boat_terminal )
( #has_/range :: BoatTerminal )

