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
title: has_duration_of_activity

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Durations

aliases:
- activity-duration
- activity
- activityDuration
- has_duration_of_activity
---

Predicate to describe the Duration of ExercisePlan.

[is_part_of:: ]

Use it like this: 
- [has_duration_of_activity::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_of_activity::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .

Length of time to engage in the activity.

Formal Predicate: 
[domain::ExercisePlan]
(name::has_duration_of_activity)
(range::Duration, QuantitativeValue)

Is [sub_property_of::]

Has [sub_properties::]
