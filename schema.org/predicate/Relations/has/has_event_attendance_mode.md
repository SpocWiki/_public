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
title: has_event_attendance_mode

linkTitle: has_event_attendance_mode
keywords: [event, attendance, mode]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- event-attendance-mode
- event_attendance_mode
- eventAttendanceMode
- has_event_attendance_mode
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_event_attendance_mode :: EventAttendanceModeEnumeration ] or 
- [ has_event_attendance_mode :: EventAttendanceModeEnumeration ] 

The eventAttendanceMode of an event indicates whether it occurs online, offline, or a mix.

Relation describes that: 
[ #has_/domain  :: Event ]
( #has_/name :: is_event_attendance_mode )
( #has_/range :: EventAttendanceModeEnumeration )

