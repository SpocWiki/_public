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
title: has_time_to_pick_up

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
- pickup-time
- pickup_time
- pickupTime
- has_time_to_pick_up
---

Predicate to describe the time of RentalCarReservation, TaxiReservation.

[is_part_of:: ]

Use it like this: 
- [has_time_to_pick_up::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/time/_to_pick_up::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

When a taxi will pick up a passenger or a rental car can be picked up.

Formal Predicate: 
[domain::RentalCarReservation, TaxiReservation]
(name::has_time_to_pick_up)
(range::DateTime)

Is [sub_property_of::]

Has [sub_properties::]
