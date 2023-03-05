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
title: has_duration_of_cooking

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
- cook-time
- cooking
- cookTime
- has_duration_of_cooking
---

Predicate to describe the Duration of Recipe.

[is_part_of:: ]

Use it like this: 
- [has_duration_of_cooking::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_of_cooking::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .


The time it takes to actually cook the dish, in &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/ISO_8601&quot;&gt;ISO 8601 duration format&lt;/a&gt;.

Formal Predicate: 
[domain::Recipe]
(name::has_duration_of_cooking)
(range::Duration)

Is [sub_property_of::performTime]

Has [sub_properties::]
