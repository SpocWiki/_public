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

title: has_text_about_tax_id
linkTitle: has_text_about_tax_id

keywords: [tax, id]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- tax-id
- tax_id
- taxID
- has_text_about_tax_id
---

Predicate to describe the Text of Organization, Person.

Use it like this: 
- [ #has_/text/_about_tax_id :: Text ] or 
- [ has_text_about_tax_id :: Text ] 

The Tax / Fiscal ID of the organization or person, e.g. the TIN in the US or the CIF/NIF in Spain.

Predicated describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: is_tax_id )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

