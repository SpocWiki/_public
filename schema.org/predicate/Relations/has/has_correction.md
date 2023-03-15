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
title: has_correction

linkTitle: has_correction
keywords: [correction]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- correction
- correction
- correction
- has_correction
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_correction :: CorrectionComment, Text, URL ] or 
- [ has_correction :: CorrectionComment, Text, URL ] 

Indicates a correction to a [[CreativeWork]], either via a [[CorrectionComment]], textually or in another document.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_correction )
( #has_/range :: CorrectionComment, Text, URL )

