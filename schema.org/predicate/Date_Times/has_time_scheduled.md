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
title: has_time_scheduled

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
- scheduled-time
- scheduled_time
- scheduledTime
- has_time_scheduled
---

Predicate to describe the date of PlanAction.

[is_part_of:: ]

Use it like this: 
- [has_time_scheduled::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/time/_scheduled::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .


The time the object is scheduled to.

Formal Predicate: 
[domain::PlanAction]
(name::has_time_scheduled)
(range::DateTime)

Is [sub_property_of::]

Has [sub_properties::]
