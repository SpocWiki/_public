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

title: has_text_about_legal_name
linkTitle: has_text_about_legal_name

keywords: [legal, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- legal-name
- legal_name
- legalName
- has_text_about_legal_name
---

Predicate to describe the Text of Organization.

Use it like this: 
- [ #has_/text/_about_legal_name :: Text ] or 
- [ has_text_about_legal_name :: Text ] 

The official name of the organization, e.g. the registered company name.

Predicated describes that: 
[ #has_/domain  :: Organization ]
( #has_/name :: is_legal_name )
( #has_/range :: Text )

