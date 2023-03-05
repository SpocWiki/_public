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
title: has_departure_airport

linkTitle: has_departure_airport
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
- departure-airport
- departure_airport
- departureAirport
- has_departure_airport
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_departure_airport :: Airport] or 
- [ has_departure_airport :: Airport] 

The airport where the flight originates.

Relation describes that: 
[ #has_/domain  :: Flight]
( #has_/name :: is_departure_airport)
( #has_/range :: Airport)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
