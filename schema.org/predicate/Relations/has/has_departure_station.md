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
keywords: [departure, station]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- departure-station
- departure_station
- departureStation
- has_departure_station
---

Use it like this: 
- [ #has/_departure_station :: TrainStation ] or 
- [ has_departure_station :: TrainStation ] 

The station from which the train departs.

Relation describes that: 
[ #has_/domain  :: TrainTrip ]
( #has_/name :: has_departure_station )
( #has_/range :: TrainStation )

