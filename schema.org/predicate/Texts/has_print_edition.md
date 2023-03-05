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

title: has_text_about_print_edition
linkTitle: has_text_about_print_edition

keywords: [print, edition]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- print-edition
- print_edition
- printEdition
- has_text_about_print_edition
---

Predicate to describe the Text of NewsArticle.

Use it like this: 
- [ #has_/text/_about_print_edition :: Text ] or 
- [ has_text_about_print_edition :: Text ] 

The edition of the print product in which the NewsArticle appears.

Predicated describes that: 
[ #has_/domain  :: NewsArticle ]
( #has_/name :: is_print_edition )
( #has_/range :: Text )

