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
title: has_date_deleted

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
- date-deleted
- date_deleted
- dateDeleted
- has_date_deleted
---

Predicate to describe the date of DataFeedItem.

[is_part_of:: ]

Use it like this: 
- [has_date_deleted::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_deleted::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

The datetime the item was removed from the DataFeed.

Formal Predicate: 
[domain::DataFeedItem]
(name::has_date_deleted)
(range::Date, DateTime)

Is [sub_property_of::]

Has [sub_properties::]
