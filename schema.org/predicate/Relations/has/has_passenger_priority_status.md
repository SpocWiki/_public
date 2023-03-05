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
title: has_passenger_priority_status

linkTitle: has_passenger_priority_status
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
- passenger-priority-status
- passenger_priority_status
- passengerPriorityStatus
- has_passenger_priority_status
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_passenger_priority_status :: QualitativeValue, Text] or 
- [ has_passenger_priority_status :: QualitativeValue, Text] 

The priority status assigned to a passenger for security or boarding (e.g. FastTrack or Priority).

Relation describes that: 
[ #has_/domain  :: FlightReservation]
( #has_/name :: is_passenger_priority_status)
( #has_/range :: QualitativeValue, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
