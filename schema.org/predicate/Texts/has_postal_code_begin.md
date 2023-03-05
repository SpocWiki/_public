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

title: has_text_about_postal_code_begin
linkTitle: has_text_about_postal_code_begin

keywords: [postal, code, begin]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- postal-code-begin
- postal_code_begin
- postalCodeBegin
- has_text_about_postal_code_begin
---

Predicate to describe the Text of PostalCodeRangeSpecification.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_postal_code_begin :: Text ] or 
- [ has_text_about_postal_code_begin :: Text ] 

First postal code in a range (included).

Predicated describes that: 
[ #has_/domain  :: PostalCodeRangeSpecification ]
( #has_/name :: has_text_about_postal_code_begin )
( #has_/range :: Text )

