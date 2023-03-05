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
title: has_work_example

linkTitle: has_work_example
keywords: [work, example]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- work-example
- work_example
- workExample
- has_work_example
---

Use it like this: 
- [ #has/_work_example :: CreativeWork ] or 
- [ has_work_example :: CreativeWork ] 

Example/instance/realization/derivation of the concept of this creative work. E.g. the paperback edition, first edition, or e-book.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_work_example )
( #has_/range :: CreativeWork )

[ #is_/inverse_of  :: exampleOfWork ]

[ #has_/sub_properties :: [ appearance, firstAppearance ] ]

