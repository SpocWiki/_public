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
title: has_date_modified

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Date

aliases:
- date-modified
- date_modified
- dateModified
- has_date_modified
---

Predicate to describe the date of CreativeWork, DataFeedItem.

[is_part_of:: ]

Use it like this: 
- [has_date_modified::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_modified::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

The date on which the CreativeWork was most recently modified or when the item's entry was modified within a DataFeed.

Formal Predicate: 
[domain::CreativeWork, DataFeedItem]
(name::has_date_modified)
(range::Date, DateTime)

Is [sub_property_of::]

Has [sub_properties::]
