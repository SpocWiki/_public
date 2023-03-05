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
title: has_sub_event

linkTitle: has_sub_event
keywords: [sub, event]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: subEvents
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- sub-event
- sub_event
- subEvent
- has_sub_event
---

Use it like this: 
- [ #has/_sub_event :: Event ] or 
- [ has_sub_event :: Event ] 

An Event that is part of this event. For example, a conference event includes many presentations, each of which is a subEvent of the conference.

Relation describes that: 
[ #has_/domain  :: Event ]
( #has_/name :: is_sub_event )
( #has_/range :: Event )

[ #is_/inverse_of  :: superEvent ]

