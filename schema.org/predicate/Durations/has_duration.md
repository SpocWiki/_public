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
title: has_duration

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Durations

aliases:
- duration
- duration
- duration
- has_duration
---

Predicate to describe the Duration of Audiobook, Episode, Event, MediaObject, Movie, MusicRecording, MusicRelease, QuantitativeValueDistribution, Schedule.

[is_part_of:: ]

Use it like this: 
- [has_duration::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .

The duration of the item (movie, audio recording, event, etc.) in &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/ISO_8601&quot;&gt;ISO 8601 date format&lt;/a&gt;.

Formal Predicate: 
[domain::Audiobook, Episode, Event, MediaObject, Movie, MusicRecording, MusicRelease, QuantitativeValueDistribution, Schedule]
(name::has_duration)
(range::Duration)

Is [sub_property_of::]

Has [sub_properties::loanTerm]
