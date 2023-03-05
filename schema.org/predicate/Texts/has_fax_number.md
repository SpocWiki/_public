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

title: has_text_about_fax_number
linkTitle: has_text_about_fax_number

keywords: [fax, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- fax-number
- fax_number
- faxNumber
- has_text_about_fax_number
---

Predicate to describe the Text of ContactPoint, Organization, Person, Place.

Use it like this: 
- [ #has_/text/_about_fax_number :: Text ] or 
- [ has_text_about_fax_number :: Text ] 

The fax number.

Predicated describes that: 
[ #has_/domain  :: ContactPoint, Organization, Person, Place ]
( #has_/name :: has_text_about_fax_number )
( #has_/range :: Text )

