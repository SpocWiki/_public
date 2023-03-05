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
title: has_time_modified

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
- modified-time
- modified_time
- modifiedTime
- has_time_modified
---

Predicate to describe the time of Reservation.

[is_part_of:: ]

Use it like this: 
- [has_time_modified::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/time/_of_modified_time::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

The date and time the reservation was modified.

Formal Predicate: 
[domain::Reservation]
(name::has_time_modified)
(range::DateTime)

Is [sub_property_of::]

Has [sub_properties::]
