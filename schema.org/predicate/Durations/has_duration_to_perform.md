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
title: has_duration_to_perform

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Durations

aliases:
- perform-time
- perform_time
- performTime
- has_duration_to_perform
---

Predicate to describe the Duration of HowTo, HowToDirection.

[is_part_of:: ]

Use it like this: 
- [has_duration_to_perform::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_to_perform::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .

The length of time it takes to perform instructions or a direction (not including time to prepare the supplies), in &lt;a href="http://en.wikipedia.org/wiki/ISO_8601"&gt;ISO 8601 duration format&lt;/a&gt;.

Formal Predicate: 
[domain::HowTo, HowToDirection]
(name::has_duration_to_perform)
(range::Duration)

Is [sub_property_of::]

Has [sub_properties::cookTime]
