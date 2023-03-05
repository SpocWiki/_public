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

title: has_text_about_honorific_prefix
linkTitle: has_text_about_honorific_prefix

keywords: [honorific, prefix]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- honorific-prefix
- honorific_prefix
- honorificPrefix
- has_text_about_honorific_prefix
---

Predicate to describe the Text of Person.

Use it like this: 
- [ #has_/text/_about_honorific_prefix :: Text ] or 
- [ has_text_about_honorific_prefix :: Text ] 

An honorific prefix preceding a Person"s name such as Dr/Mrs/Mr.

Predicated describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_text_about_honorific_prefix )
( #has_/range :: Text )

