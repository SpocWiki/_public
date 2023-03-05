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
title: has_read_by

linkTitle: has_read_by
keywords: [read, by]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- read-by
- read_by
- readBy
- has_read_by
---

[ #is_/part_of :: https://bib.schema.org ]

Use it like this: 
- [ #has/_read_by :: Person ] or 
- [ has_read_by :: Person ] 

A person who reads (performs) the audiobook.

Relation describes that: 
[ #has_/domain  :: Audiobook ]
( #has_/name :: is_read_by )
( #has_/range :: Person )

[ #is_/sub_property_of  :: actor ]

