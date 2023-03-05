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

title: has_text_about_value_pattern
linkTitle: has_text_about_value_pattern

keywords: [value, pattern]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- value-pattern
- value_pattern
- valuePattern
- has_text_about_value_pattern
---

Predicate to describe the Text of PropertyValueSpecification.

Use it like this: 
- [ #has_/text/_about_value_pattern :: Text ] or 
- [ has_text_about_value_pattern :: Text ] 

Specifies a regular expression for testing literal values according to the HTML spec.

Predicated describes that: 
[ #has_/domain  :: PropertyValueSpecification ]
( #has_/name :: has_text_about_value_pattern )
( #has_/range :: Text )

