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

title: has_text_about_family_name
linkTitle: has_text_about_family_name

keywords: [family, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- family-name
- family_name
- familyName
- has_text_about_family_name
---

Predicate to describe the Text of Person.

Use it like this: 
- [ #has_/text/_about_family_name :: Text ] or 
- [ has_text_about_family_name :: Text ] 

Family name. In the U.S., the last name of a Person.

Predicated describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_text_about_family_name )
( #has_/range :: Text )

