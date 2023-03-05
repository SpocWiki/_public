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
title: has_date_created

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
- date-created
- date_created
- dateCreated
- has_date_created
---

Predicate to describe the date of CreativeWork, DataFeedItem.

[is_part_of:: ]

Use it like this: 
- [has_date_created::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_created::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .


The date on which the CreativeWork was created or the item was added to a DataFeed.

Formal Predicate: 
[domain::CreativeWork, DataFeedItem]
(name::has_date_created)
(range::Date, DateTime)

Is [sub_property_of::]

Has [sub_properties::legislationDate]
