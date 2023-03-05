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
title: has_job_title

linkTitle: has_job_title
keywords: [job, title]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- job-title
- job_title
- jobTitle
- has_job_title
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_job_title :: DefinedTerm, Text ] or 
- [ has_job_title :: DefinedTerm, Text ] 

The job title of the person (for example, Financial Manager).

Relation describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: is_job_title )
( #has_/range :: DefinedTerm, Text )

