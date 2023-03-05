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
title: has_time_of_comment

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
- comment-time
- comment_time
- commentTime
- has_time_of_comment
---

Predicate to describe the time of UserComments.

[is_part_of:: ]

Use it like this: 
- [has_time_of_comment::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/time/_of_comment_time::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .


The time at which the UserComment was made.

Formal Predicate: 
[domain::UserComments]
(name::has_time_of_comment)
(range::Date, DateTime)

