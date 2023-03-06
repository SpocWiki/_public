---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Count
publish: true

# Hugo Tags
type: Predi_Count

title: has_number_of_clip_number
linkTitle: has_number_of_clip_number

keywords: [clip_number]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- clip-number
- clip_number
- clipNumber
- has_number_of_clip
---

Predicate to describe the Number of Clip.

Use it like this: 
- [ #has_/number/_of_clip :: Integer, Text ] or 
- [ has_number_of_clip :: Integer, Text ] 

Position of the clip within an ordered group of clips.

Predicate describes that: 
[ #has_/domain  :: Clip ]
( #has_/name :: has_number_of_clip )
( #has_/range :: Integer, Text )

[ #is_/sub_property_of  :: position ]

