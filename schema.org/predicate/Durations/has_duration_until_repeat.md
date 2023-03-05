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
title: has_duration_until_repeat

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
- repeat-frequency
- repeat_frequency
- repeatFrequency
- has_duration_until_repeat
---

Predicate to describe the Duration of Schedule.

[is_part_of:: pending:]

Use it like this: 
- [has_duration_until_repeat::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_until_repeat::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .

Defines the frequency at which &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Event&quot;&gt;Event&lt;/a&gt;s will occur according to a schedule &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Schedule&quot;&gt;Schedule&lt;/a&gt;. The intervals between
      events should be defined as a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Duration&quot;&gt;Duration&lt;/a&gt; of time.

Formal Predicate: 
[domain::Schedule]
(name::has_duration_until_repeat)
(range::Duration, Text)

Is [sub_property_of::frequency]

Has [sub_properties::]
