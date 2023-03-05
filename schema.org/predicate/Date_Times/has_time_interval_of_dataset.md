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
title: has_time_interval_of_dataset

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: temporalCoverage

tags:
- schema.org/Predicate/Date

aliases:
- dataset-time-interval
- dataset_time_interval
- datasetTimeInterval
- has_date_interval_of_dataset
---

Predicate to describe the date of Dataset.

[is_part_of:: ]

Use it like this: 
- [has_time_interval_of_dataset::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/time/_interval_of_dataset::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

The range of temporal applicability of a dataset, e.g. for a 2011 census dataset, the year 2011 (in ISO 8601 time interval format).

Formal Predicate: 
[domain::Dataset]
(name::has_date_interval_of_dataset)
(range::DateTime)

Is [sub_property_of::]

Has [sub_properties::]
