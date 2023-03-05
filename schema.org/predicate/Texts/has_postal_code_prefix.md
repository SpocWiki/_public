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

title: has_text_about_postal_code_prefix
linkTitle: has_text_about_postal_code_prefix

keywords: [postal, code, prefix]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- postal-code-prefix
- postal_code_prefix
- postalCodePrefix
- has_text_about_postal_code_prefix
---

Predicate to describe the Text of DefinedRegion.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_postal_code_prefix :: Text ] or 
- [ has_text_about_postal_code_prefix :: Text ] 

A defined range of postal codes indicated by a common textual prefix. Used for non-numeric systems such as UK.

Predicated describes that: 
[ #has_/domain  :: DefinedRegion ]
( #has_/name :: is_postal_code_prefix )
( #has_/range :: Text )

