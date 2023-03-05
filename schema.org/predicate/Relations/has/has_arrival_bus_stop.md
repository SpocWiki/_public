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
title: has_arrival_bus_stop

linkTitle: has_arrival_bus_stop
keywords: [arrival, bus, stop]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- arrival-bus-stop
- arrival_bus_stop
- arrivalBusStop
- has_arrival_bus_stop
---

Use it like this: 
- [ #has/_arrival_bus_stop :: BusStation, BusStop ] or 
- [ has_arrival_bus_stop :: BusStation, BusStop ] 

The stop or station from which the bus arrives.

Relation describes that: 
[ #has_/domain  :: BusTrip ]
( #has_/name :: is_arrival_bus_stop )
( #has_/range :: BusStation, BusStop )

