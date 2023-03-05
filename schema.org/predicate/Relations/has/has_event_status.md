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
title: has_event_status

linkTitle: has_event_status
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
- event-status
- event_status
- eventStatus
- has_event_status
---

Use it like this: 
- [ #has/_event_status :: EventStatusType] or 
- [ has_event_status :: EventStatusType] 

An eventStatus of an event represents its status; particularly useful when an event is cancelled or rescheduled.

Relation describes that: 
[ #has_/domain  :: Event]
( #has_/name :: is_event_status)
( #has_/range :: EventStatusType)

