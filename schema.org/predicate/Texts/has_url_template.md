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

title: has_text_about_url_template
linkTitle: has_text_about_url_template

keywords: [url, template]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- url-template
- url_template
- urlTemplate
- has_text_about_url_template
---

Predicate to describe the Text of EntryPoint.

Use it like this: 
- [ #has_/text/_about_url_template :: Text ] or 
- [ has_text_about_url_template :: Text ] 

An url template (RFC6570) that will be used to construct the target of the execution of the action.

Predicated describes that: 
[ #has_/domain  :: EntryPoint ]
( #has_/name :: is_url_template )
( #has_/range :: Text )

