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
title: has_date_to_start_job

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Date

aliases:
- job-start-date
- job_start_date
- jobStartDate
- has_date_to_start_job
---

Predicate to describe the date of JobPosting.

[is_part_of:: pending:]

Use it like this: 
- [has_date_to_start_job::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_to_start_job::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

The date on which a successful applicant for this job would be expected to start work. Choose a specific date in the future or use the jobImmediateStart property to indicate the position is to be filled as soon as possible.

Formal Predicate: 
[domain::JobPosting]
(name::has_date_to_start_job)
(range::Date, Text)

Is [sub_property_of::]

Has [sub_properties::]
