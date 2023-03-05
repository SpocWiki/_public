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

title: has_text_about_vat_id
linkTitle: has_text_about_vat_id

keywords: [vat, id]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- vat-id
- vat_id
- vatID
- has_text_about_vat_id
---

Predicate to describe the Text of Organization, Person.

Use it like this: 
- [ #has_/text/_about_vat_id :: Text ] or 
- [ has_text_about_vat_id :: Text ] 

The Value-added Tax ID of the organization or person.

Predicated describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: has_text_about_vat_id )
( #has_/range :: Text )

