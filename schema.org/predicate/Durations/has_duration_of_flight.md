---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Duration
publish: true

# Hugo Tags
type: Predi_Duration
title: has_duration_of_flight

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Durations

aliases:
- estimated-flight-duration
- flight
- estimatedFlightDuration
- has_duration_of_flight
---

Predicate to describe the Duration of Flight.

[is_part_of:: ]

Use it like this: 
- [has_duration_of_flight::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_of_flight::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .

The estimated time the flight will take.

Formal Predicate: 
[domain::Flight]
(name::has_duration_of_flight)
(range::Duration, Text)

Is [sub_property_of::]

Has [sub_properties::]
