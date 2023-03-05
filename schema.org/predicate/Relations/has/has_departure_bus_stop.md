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
title: has_departure_bus_stop

linkTitle: has_departure_bus_stop
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
- departure-bus-stop
- departure_bus_stop
- departureBusStop
- has_departure_bus_stop
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_departure_bus_stop :: BusStation, BusStop] or 
- [ has_departure_bus_stop :: BusStation, BusStop] 

The stop or station from which the bus departs.

Relation describes that: 
[ #has_/domain  :: BusTrip]
( #has_/name :: is_departure_bus_stop)
( #has_/range :: BusStation, BusStop)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

