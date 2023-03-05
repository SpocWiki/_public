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

title: has_text_about_given_name
linkTitle: has_text_about_given_name

keywords: [given, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- given-name
- given_name
- givenName
- has_text_about_given_name
---

Predicate to describe the Text of Person.

Use it like this: 
- [ #has_/text/_about_given_name :: Text ] or 
- [ has_text_about_given_name :: Text ] 

Given name. In the U.S., the first name of a Person.

Predicated describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_text_about_given_name )
( #has_/range :: Text )

