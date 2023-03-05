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

title: has_text_about_lei_code
linkTitle: has_text_about_lei_code

keywords: [lei, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- lei-code
- lei_code
- leiCode
- has_text_about_lei_code
---

Predicate to describe the Text of Organization.

Use it like this: 
- [ #has_/text/_about_lei_code :: Text ] or 
- [ has_text_about_lei_code :: Text ] 

An organization identifier that uniquely identifies a legal entity as defined in ISO 17442.

Predicated describes that: 
[ #has_/domain  :: Organization ]
( #has_/name :: is_lei_code )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

