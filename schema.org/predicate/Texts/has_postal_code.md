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

title: has_text_about_postal_code
linkTitle: has_text_about_postal_code

keywords: [postal, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- postal-code
- postal_code
- postalCode
- has_text_about_postal_code
---

Predicate to describe the Text of DefinedRegion, GeoCoordinates, GeoShape, PostalAddress.

Use it like this: 
- [ #has_/text/_about_postal_code :: Text ] or 
- [ has_text_about_postal_code :: Text ] 

The postal code. For example, 94043.

Predicated describes that: 
[ #has_/domain  :: DefinedRegion, GeoCoordinates, GeoShape, PostalAddress ]
( #has_/name :: has_text_about_postal_code )
( #has_/range :: Text )

