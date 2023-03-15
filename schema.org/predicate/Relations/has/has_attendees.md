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
title: has_attendees

linkTitle: has_attendees
keywords: [attendees]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- attendees
- attendees
- attendees
- has_attendees
---

[ superseded_by :: attendee ]

Use it like this: 
- [ #has/_attendee :: Organization, Person ] or 
- [ has_attendee :: Organization, Person ] 

A person attending the event.

Relation describes that: 
[ #has_/domain  :: Event ]
( #has_/name :: has_attendees )
( #has_/range :: Organization, Person )

