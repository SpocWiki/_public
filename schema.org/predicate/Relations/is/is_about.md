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
title: is_about

linkTitle: is_about
keywords: [about]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- about
- about
- about
- is_about
---

Use it like this: 
- [ #is/_about :: Thing ] or 
- [ is_about :: Thing ] 

The subject matter of the content.

Relation describes that: 
[ #has_/domain  :: CommunicateAction, CreativeWork, Event ]
( #has_/name :: is_about )
( #has_/range :: Thing )

[ #is_/inverse_of  :: [[has_subject_of]] ]

[ #has_/sub_properties :: [ mainEntity ] ]

