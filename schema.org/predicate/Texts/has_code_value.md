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

title: has_text_about_code_value
linkTitle: has_text_about_code_value

keywords: [code, value]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- code-value
- code_value
- codeValue
- has_text_about_code_value
---

Predicate to describe the Text of CategoryCode, MedicalCode.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_code_value :: Text ] or 
- [ has_text_about_code_value :: Text ] 

A short textual code that uniquely identifies the value.

Predicated describes that: 
[ #has_/domain  :: CategoryCode, MedicalCode ]
( #has_/name :: has_text_about_code_value )
( #has_/range :: Text )

[ #is_/sub_property_of  :: termCode ]

