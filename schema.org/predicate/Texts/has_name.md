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

title: has_text_about_name
linkTitle: has_text_about_name

keywords: [name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- name
- name
- name
- has_text_about_name
---

Predicate to describe the Text of Thing.

Use it like this: 
- [ #has_/text/_about_name :: Text ] or 
- [ has_text_about_name :: Text ] 

The name of the item.

Predicated describes that: 
[ #has_/domain  :: Thing ]
( #has_/name :: has_text_about_name )
( #has_/range :: Text )

[ #is_/sub_property_of  :: http://www.w3.org/2000/01/rdf-schema#label ]

