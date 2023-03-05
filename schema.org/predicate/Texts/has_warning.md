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

title: has_text_about_warning
linkTitle: has_text_about_warning

keywords: [warning]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- warning
- warning
- warning
- has_text_about_warning
---

Predicate to describe the Text of Drug.

Use it like this: 
- [ #has_/text/_about_warning :: Text, URL ] or 
- [ has_text_about_warning :: Text, URL ] 

Any FDA or other warnings about the drug (text or URL).

Predicated describes that: 
[ #has_/domain  :: Drug ]
( #has_/name :: has_text_about_warning )
( #has_/range :: Text, URL )

