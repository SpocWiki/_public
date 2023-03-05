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
title: has_work_featured

linkTitle: has_work_featured
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
- work-featured
- work_featured
- workFeatured
- has_work_featured
---

Use it like this: 
- [ #has/_work_featured :: CreativeWork] or 
- [ has_work_featured :: CreativeWork] 

A work featured in some event, e.g. exhibited in an ExhibitionEvent.
       Specific subproperties are available for workPerformed (e.g. a play), or a workPresented (a Movie at a ScreeningEvent).

Relation describes that: 
[ #has_/domain  :: Event]
( #has_/name :: is_work_featured)
( #has_/range :: CreativeWork)

[ #has_/sub_properties :: workPerformed, workPresented]

