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
title: has_duration_of_billing_period

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
- billing-period
- billing_period
- billingPeriod
- has_duration_of_billing_period
---

Predicate to describe the Duration of Invoice.

[is_part_of:: ]

Use it like this: 
- [has_duration_of_billing_period::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_of_billing_period::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .

The time interval used to compute the invoice.

Formal Predicate: 
[domain::Invoice]
(name::has_duration_of_billing_period)
(range::Duration)

Is [sub_property_of::]

Has [sub_properties::]
