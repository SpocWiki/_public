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
title: has_date_of_scheduled_payment

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
- scheduled-payment-date
- scheduled_payment_date
- scheduledPaymentDate
- has_date_of_scheduled_payment
---

Predicate to describe the date of Invoice.

[is_part_of:: ]

Use it like this: 
- [has_date_of_scheduled_payment::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_of_scheduled_payment::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .


The date the invoice is scheduled to be paid.

Formal Predicate: 
[domain::Invoice]
(name::has_date_of_scheduled_payment)
(range::Date)

Is [sub_property_of::]

Has [sub_properties::]
