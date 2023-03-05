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

title: has_text_about_address_locality
linkTitle: has_text_about_address_locality

keywords: [address, locality]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- address-locality
- address_locality
- addressLocality
- has_text_about_address_locality
---

Predicate to describe the Text of PostalAddress.

Use it like this: 
- [ #has_/text/_about_address_locality :: Text ] or 
- [ has_text_about_address_locality :: Text ] 

The locality in which the street address is, and which is in the region. For example, Mountain View.

Predicated describes that: 
[ #has_/domain  :: PostalAddress ]
( #has_/name :: has_text_about_address_locality )
( #has_/range :: Text )

