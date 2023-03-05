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

title: has_text_about_email
linkTitle: has_text_about_email

keywords: [email]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- email
- email
- email
- has_text_about_email
---

Predicate to describe the Text of ContactPoint, Organization, Person.

Use it like this: 
- [ #has_/text/_about_email :: Text ] or 
- [ has_text_about_email :: Text ] 

Email address.

Predicated describes that: 
[ #has_/domain  :: ContactPoint, Organization, Person ]
( #has_/name :: is_email )
( #has_/range :: Text )

