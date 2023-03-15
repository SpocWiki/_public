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
title: is_by_day

linkTitle: is_by_day
keywords: [by, day]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- by-day
- by_day
- byDay
- is_by_day
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_by_day :: DayOfWeek, Text ] or 
- [ is_by_day :: DayOfWeek, Text ] 

Defines the day(s) of the week on which a recurring [[Event]] takes place. May be specified using either [[DayOfWeek]], or alternatively [[Text]] conforming to iCal's syntax for byDay recurrence rules.

Relation describes that: 
[ #has_/domain  :: Schedule ]
( #has_/name :: is_by_day )
( #has_/range :: DayOfWeek, Text )

