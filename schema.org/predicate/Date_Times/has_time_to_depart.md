---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Date_Time
publish: true

# Hugo Tags
type: Predi_Date_Time
title: has_time_to_depart

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Date

aliases:
- departure-time
- departure_time
- departureTime
- has_time_to_depart
---

Predicate to describe the time of Trip.

[is_part_of:: ]

Use it like this: 
- [has_time_to_depart::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/time/_to_depart::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Date Format](../../../ISO/ISO_8601-Date_Time) .

The expected departure time.

Formal Predicate: 
[domain::Trip]
(name::has_time_to_depart)
(range::DateTime, Time)

Is [sub_property_of::]

Has [sub_properties::]
