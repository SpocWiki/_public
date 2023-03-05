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

title: has_text_about_terms_of_service
linkTitle: has_text_about_terms_of_service

keywords: [terms, of, service]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- terms-of-service
- terms_of_service
- termsOfService
- has_text_about_terms_of_service
---

Predicate to describe the Text of Service.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_terms_of_service :: Text, URL ] or 
- [ has_text_about_terms_of_service :: Text, URL ] 

Human-readable terms of service documentation.

Predicated describes that: 
[ #has_/domain  :: Service ]
( #has_/name :: has_text_about_terms_of_service )
( #has_/range :: Text, URL )

