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
title: has_date_of_previous_start

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Date

aliases:
- previous-start-date
- previous_start_date
- previousStartDate
- has_date_of_previous_start
---

Predicate to describe the date of Event.

[is_part_of:: ]

Use it like this: 
- [has_date_of_previous_start::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_of_previous_start::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

Used in conjunction with eventStatus for rescheduled or cancelled events. This property contains the previously scheduled start date. For rescheduled events, the startDate property should be used for the newly scheduled start date. In the (rare) case of an event that has been postponed and rescheduled multiple times, this field may be repeated.

Formal Predicate: 
[domain::Event]
(name::has_date_of_previous_start)
(range::Date)

Is [sub_property_of::]

Has [sub_properties::]
