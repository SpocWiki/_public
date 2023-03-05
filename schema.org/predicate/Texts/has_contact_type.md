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

title: has_text_about_contact_type
linkTitle: has_text_about_contact_type

keywords: [contact, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- contact-type
- contact_type
- contactType
- has_text_about_contact_type
---

Predicate to describe the Text of ContactPoint.

Use it like this: 
- [ #has_/text/_about_contact_type :: Text ] or 
- [ has_text_about_contact_type :: Text ] 

A person or organization can have different contact points, for different purposes. For example, a sales contact point, a PR contact point and so on. This property is used to specify the kind of contact point.

Predicated describes that: 
[ #has_/domain  :: ContactPoint ]
( #has_/name :: has_text_about_contact_type )
( #has_/range :: Text )

