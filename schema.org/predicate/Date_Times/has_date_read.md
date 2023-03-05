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
title: has_date_read

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Date

aliases:
- date-read
- date_read
- dateRead
- has_date_read
---

Predicate to describe the date of Message.

[is_part_of:: ]

Use it like this: 
- [has_date_read::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_read::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

The date/time at which the message has been read by the recipient if a single recipient exists.

Formal Predicate: 
[domain::Message]
(name::has_date_read)
(range::Date, DateTime)

Is [sub_property_of::]

Has [sub_properties::]
