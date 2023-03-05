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
title: has_date_of_legislation

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
- legislation-date
- legislation_date
- legislationDate
- has_date_of_legislation
---

Predicate to describe the date of Legislation.

[is_part_of:: pending:]

Use it like this: 
- [has_date_of_legislation::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_of_legislation::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .


The date of adoption or signature of the legislation. This is the date at which the text is officially aknowledged to be a legislation, even though it might not even be published or in force.

Formal Predicate: 
[domain::Legislation]
(name::has_date_of_legislation)
(range::Date)

Is [sub_property_of::dateCreated]

Has [sub_properties::]
