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

title: has_text_about_default_value
linkTitle: has_text_about_default_value

keywords: [default, value]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- default-value
- default_value
- defaultValue
- has_text_about_default_value
---

Predicate to describe the Text of PropertyValueSpecification.

Use it like this: 
- [ #has_/text/_about_default_value :: Text, Thing ] or 
- [ has_text_about_default_value :: Text, Thing ] 

The default value of the input.  For properties that expect a literal, the default is a literal value, for properties that expect an object, it"s an ID reference to one of the current values.

Predicated describes that: 
[ #has_/domain  :: PropertyValueSpecification ]
( #has_/name :: is_default_value )
( #has_/range :: Text, Thing )

