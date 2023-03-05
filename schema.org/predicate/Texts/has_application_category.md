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

title: has_text_about_application_category
linkTitle: has_text_about_application_category

keywords: [application, category]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- application-category
- application_category
- applicationCategory
- has_text_about_application_category
---

Predicate to describe the Text of SoftwareApplication.

Use it like this: 
- [ #has_/text/_about_application_category :: Text, URL ] or 
- [ has_text_about_application_category :: Text, URL ] 

Type of software application, e.g. "Game, Multimedia".

Predicated describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: is_application_category )
( #has_/range :: Text, URL )

