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

title: has_text_about_street_address
linkTitle: has_text_about_street_address

keywords: [street, address]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- street-address
- street_address
- streetAddress
- has_text_about_street_address
---

Predicate to describe the Text of PostalAddress.

Use it like this: 
- [ #has_/text/_about_street_address :: Text ] or 
- [ has_text_about_street_address :: Text ] 

The street address. For example, 1600 Amphitheatre Pkwy.

Predicated describes that: 
[ #has_/domain  :: PostalAddress ]
( #has_/name :: is_street_address )
( #has_/range :: Text )

