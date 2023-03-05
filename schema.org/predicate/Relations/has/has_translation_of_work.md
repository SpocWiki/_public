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
title: has_translation_of_work

linkTitle: has_translation_of_work
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
- translation-of-work
- translation_of_work
- translationOfWork
- has_translation_of_work
---

[ #is_/part_of :: https://bib.schema.org]

Use it like this: 
- [ #has/_translation_of_work :: CreativeWork] or 
- [ has_translation_of_work :: CreativeWork] 

The work that this work has been translated from. E.g. ???? is a translationOf �On the Origin of Species�.

Relation describes that: 
[ #has_/domain  :: CreativeWork]
( #has_/name :: is_translation_of_work)
( #has_/range :: CreativeWork)

[ #is_/inverse_of  :: workTranslation]

