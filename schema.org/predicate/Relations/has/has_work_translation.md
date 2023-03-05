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
title: has_work_translation

linkTitle: has_work_translation
keywords: [work, translation]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- work-translation
- work_translation
- workTranslation
- has_work_translation
---

[ #is_/part_of :: https://bib.schema.org ]

Use it like this: 
- [ #has/_work_translation :: CreativeWork ] or 
- [ has_work_translation :: CreativeWork ] 

A work that is a translation of the content of this work. E.g. ??? has an English workTranslation �Journey to the West�, a German workTranslation �Monkeys Pilgerfahrt� and a Vietnamese  translation T�y du k� b�nh kh?o.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_work_translation )
( #has_/range :: CreativeWork )

[ #is_/inverse_of  :: translationOfWork ]

