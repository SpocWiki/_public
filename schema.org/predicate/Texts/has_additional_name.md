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

title: has_text_about_additional_name
linkTitle: has_text_about_additional_name

keywords: [additional, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- additional-name
- additional_name
- additionalName
- has_text_about_additional_name
---

Predicate to describe the Text of Person.

Use it like this: 
- [ #has_/text/_about_additional_name :: Text ] or 
- [ has_text_about_additional_name :: Text ] 

An additional name for a Person, can be used for a middle name.

Predicated describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_text_about_additional_name )
( #has_/range :: Text )

[ #is_/sub_property_of  :: alternateName ]

