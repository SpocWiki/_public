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
title: has_departure_station

linkTitle: has_departure_station
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
- departure-station
- departure_station
- departureStation
- has_departure_station
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_departure_station :: TrainStation] or 
- [ has_departure_station :: TrainStation] 

The station from which the train departs.

Relation describes that: 
[ #has_/domain  :: TrainTrip]
( #has_/name :: is_departure_station)
( #has_/range :: TrainStation)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
