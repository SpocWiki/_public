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

title: has_text_about_disambiguating_description
linkTitle: has_text_about_disambiguating_description

keywords: [disambiguating, description]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- disambiguating-description
- disambiguating_description
- disambiguatingDescription
- has_text_about_disambiguating_description
---

Predicate to describe the Text of Thing.

Use it like this: 
- [ #has_/text/_about_disambiguating_description :: Text ] or 
- [ has_text_about_disambiguating_description :: Text ] 

A sub property of description. A short description of the item used to disambiguate from other, similar items. Information from other properties (in particular, name) may be necessary for the description to be useful for disambiguation.

Predicated describes that: 
[ #has_/domain  :: Thing ]
( #has_/name :: is_disambiguating_description )
( #has_/range :: Text )

[ #is_/sub_property_of  :: description ]

