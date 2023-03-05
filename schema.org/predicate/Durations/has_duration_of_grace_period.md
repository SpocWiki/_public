---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Duration
publish: true

# Hugo Tags
type: Predi_Duration
title: has_duration_of_grace_period

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Durations

aliases:
- grace-period
- grace_period
- gracePeriod
- has_duration_of_grace_period
---

Predicate to describe the Duration of LoanOrCredit.

[is_part_of:: pending:]

Use it like this: 
- [has_duration_of_grace_period::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_of_grace_period::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .


The period of time after any due date that the borrower has to fulfil its obligations before a default (failure to pay) is deemed to have occurred.

Formal Predicate: 
[domain::LoanOrCredit]
(name::has_duration_of_grace_period)
(range::Duration)

Is [sub_property_of::]

Has [sub_properties::]
