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

title: has_text_about_description
linkTitle: has_text_about_description

keywords: [description]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- description
- description
- description
- has_text_about_description
---

Predicate to describe the Text of Thing.

Use it like this: 
- [ #has_/text/_about_description :: Text ] or 
- [ has_text_about_description :: Text ] 

A description of the item.

Predicated describes that: 
[ #has_/domain  :: Thing ]
( #has_/name :: is_description )
( #has_/range :: Text )

[ #has_/sub_properties :: [ disambiguatingDescription, interpretedAsClaim, originalMediaContextDescription, sha256 ] ]

