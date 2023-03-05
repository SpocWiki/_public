---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_text_about_alternate_name
linkTitle: has_text_about_alternate_name

keywords: [alternate, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- alternate-name
- alternate_name
- alternateName
- has_text_about_alternate_name
---

Predicate to describe the Text of Thing.

Use it like this: 
- [ #has_/text/_about_alternate_name :: Text ] or 
- [ has_text_about_alternate_name :: Text ] 

An alias for the item.

Predicated describes that: 
[ #has_/domain  :: Thing ]
( #has_/name :: is_alternate_name )
( #has_/range :: Text )

[ #has_/sub_properties :: [ additionalName ] ]

