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
title: has_steps

linkTitle: has_steps
keywords: [steps]
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: step

tags:
- schema.org/Predicate/Relation

aliases:
- steps
- steps
- steps
- has_steps
---

Use it like this: 
- [ #has/_steps :: CreativeWork, ItemList, Text ] or 
- [ has_steps :: CreativeWork, ItemList, Text ] 

A single step item (as HowToStep, text, document, video, etc.) or a HowToSection (originally misnamed 'steps'; 'step' is preferred).

Relation describes that: 
[ #has_/domain  :: HowTo, HowToSection ]
( #has_/name :: is_steps )
( #has_/range :: CreativeWork, ItemList, Text )

