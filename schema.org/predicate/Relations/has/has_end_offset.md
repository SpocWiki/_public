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
title: has_end_offset

linkTitle: has_end_offset
keywords: [end, offset]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- end-offset
- end_offset
- endOffset
- has_end_offset
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_end_offset :: HyperTocEntry, Number ] or 
- [ has_end_offset :: HyperTocEntry, Number ] 

The end time of the clip expressed as the number of seconds from the beginning of the work.

Relation describes that: 
[ #has_/domain  :: Clip ]
( #has_/name :: has_end_offset )
( #has_/range :: HyperTocEntry, Number )

