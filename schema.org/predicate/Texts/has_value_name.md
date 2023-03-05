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

title: has_text_about_value_name
linkTitle: has_text_about_value_name

keywords: [value, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- value-name
- value_name
- valueName
- has_text_about_value_name
---

Predicate to describe the Text of PropertyValueSpecification.

Use it like this: 
- [ #has_/text/_about_value_name :: Text ] or 
- [ has_text_about_value_name :: Text ] 

Indicates the name of the PropertyValueSpecification to be used in URL templates and form encoding in a manner analogous to HTML"s input@name.

Predicated describes that: 
[ #has_/domain  :: PropertyValueSpecification ]
( #has_/name :: has_text_about_value_name )
( #has_/range :: Text )

