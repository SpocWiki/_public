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
title: is_in_code_set

linkTitle: is_in_code_set
keywords: [in, code, set]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- in-code-set
- in_code_set
- inCodeSet
- is_in_code_set
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #is/_in_code_set :: CategoryCodeSet, URL ] or 
- [ is_in_code_set :: CategoryCodeSet, URL ] 

A [[CategoryCodeSet]] that contains this category code.

Relation describes that: 
[ #has_/domain  :: CategoryCode ]
( #has_/name :: is_in_code_set )
( #has_/range :: CategoryCodeSet, URL )

[ #is_/sub_property_of  :: inDefinedTermSet ]

