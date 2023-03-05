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
title: has_time_of_coverage_start

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
- coverage-start-time
- coverage_start_time
- coverageStartTime
- has_time_of_coverage_start
---

Predicate to describe the time of LiveBlogPosting.

[is_part_of:: ]

Use it like this: 
- [has_time_of_coverage_start::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/time/_of_coverage_start::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Date Format](../../../ISO/ISO_8601-Date_Time) .

The time when the live blog will begin covering the Event. Note that coverage may begin before the Event&#x27;s start time. The LiveBlogPosting may also be created before coverage begins.

Formal Predicate: 
[domain::LiveBlogPosting]
(name::has_time_of_coverage_start)
(range::DateTime)

Is [sub_property_of::]

Has [sub_properties::]
