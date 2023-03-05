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
title: has_date_available_through

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
- available-through
- available_through
- availableThrough
- has_date_available_through
---

Predicate to describe the date of DeliveryEvent.

[is_part_of:: ]

Use it like this: 
- [has_date_available_through::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_available_through::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .


After this date, the item will no longer be available for pickup.

Formal Predicate: 
[domain::DeliveryEvent]
(name::has_date_available_through)
(range::DateTime)

Is [sub_property_of::]

Has [sub_properties::]