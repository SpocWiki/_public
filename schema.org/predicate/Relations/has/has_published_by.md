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
title: has_published_by

linkTitle: has_published_by
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
- published-by
- published_by
- publishedBy
- has_published_by
---

[ #is_/part_of :: https://bib.schema.org]

Use it like this: 
- [ #has/_published_by :: Organization, Person] or 
- [ has_published_by :: Organization, Person] 

An agent associated with the publication event.

Relation describes that: 
[ #has_/domain  :: PublicationEvent]
( #has_/name :: is_published_by)
( #has_/range :: Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
