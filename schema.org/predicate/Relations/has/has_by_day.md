---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_by_day

linkTitle: has_by_day
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- by-day
- by_day
- byDay
- has_by_day
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_by_day :: DayOfWeek, Text] or 
- [ has_by_day :: DayOfWeek, Text] 

Defines the day(s) of the week on which a recurring &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Event&quot;&gt;Event&lt;/a&gt; takes place. May be specified using either &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/DayOfWeek&quot;&gt;DayOfWeek&lt;/a&gt;, or alternatively &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Text&quot;&gt;Text&lt;/a&gt; conforming to iCal&#x27;s syntax for byDay recurrence rules.

Relation describes that: 
[ #has_/domain  :: Schedule]
( #has_/name :: is_by_day)
( #has_/range :: DayOfWeek, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

