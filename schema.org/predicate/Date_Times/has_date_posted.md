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
title: has_date_posted

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
- date-posted
- date_posted
- datePosted
- has_date_posted
---

Predicate to describe the date of CDCPMDRecord, JobPosting, RealEstateListing, SpecialAnnouncement.

[is_part_of:: ]

Use it like this: 
- [has_date_posted::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_posted::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

Publication date of an online listing.

Formal Predicate: 
[domain::CDCPMDRecord, JobPosting, RealEstateListing, SpecialAnnouncement]
(name::has_date_posted)
(range::Date, DateTime)

Is [sub_property_of::]

Has [sub_properties::]
