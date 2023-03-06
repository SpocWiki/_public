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
title: has_date_of_temporal

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Date

aliases:
- temporal
- temporal
- temporal
- has_date_of_temporal
---

Predicate to describe the date of CreativeWork.

[is_part_of:: ]

Use it like this: 
- [has_date_of_temporal::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_of_temporal::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

The "temporal" property can be used in cases where more specific properties
(e.g. &lt;a class="localLink" href="/temporalCoverage"&gt;temporalCoverage&lt;/a&gt;, &lt;a class="localLink" href="/dateCreated"&gt;dateCreated&lt;/a&gt;, &lt;a class="localLink" href="/dateModified"&gt;dateModified&lt;/a&gt;, &lt;a class="localLink" href="/datePublished"&gt;datePublished&lt;/a&gt;) are not known to be appropriate.

Formal Predicate: 
[domain::CreativeWork]
(name::has_date_of_temporal)
(range::DateTime, Text)

Is [sub_property_of::]

Has [sub_properties::]
