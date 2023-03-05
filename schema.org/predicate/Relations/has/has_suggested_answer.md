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
title: has_suggested_answer

linkTitle: has_suggested_answer
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
- suggested-answer
- suggested_answer
- suggestedAnswer
- has_suggested_answer
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_suggested_answer :: Answer, ItemList] or 
- [ has_suggested_answer :: Answer, ItemList] 

An answer (possibly one of several, possibly incorrect) to a Question, e.g. on a Question/Answer site.

Relation describes that: 
[ #has_/domain  :: Question]
( #has_/name :: is_suggested_answer)
( #has_/range :: Answer, ItemList)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: acceptedAnswer]
