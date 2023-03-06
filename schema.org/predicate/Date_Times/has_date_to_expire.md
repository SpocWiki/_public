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
title: has_date_to_expire

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Date

aliases:
- expires
- expires
- expires
- has_date_to_expire
---

Predicate to describe the date of CreativeWork.

[is_part_of:: ]

Use it like this: 
- [has_date_to_expire::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_to_expire::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .

Date the content expires and is no longer useful or available. For example a &lt;a class="localLink" href="/VideoObject"&gt;VideoObject&lt;/a&gt; or &lt;a class="localLink" href="/NewsArticle"&gt;NewsArticle&lt;/a&gt; whose availability or relevance is time-limited, or a &lt;a class="localLink" href="/ClaimReview"&gt;ClaimReview&lt;/a&gt; fact check whose publisher wants to indicate that it may no longer be relevant (or helpful to highlight) after some date.

Formal Predicate: 
[domain::CreativeWork]
(name::has_date_to_expire)
(range::Date, DateTime)

Is [sub_property_of::]

Has [sub_properties::]
