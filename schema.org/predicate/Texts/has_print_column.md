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

title: has_text_about_print_column
linkTitle: has_text_about_print_column

keywords: [print, column]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- print-column
- print_column
- printColumn
- has_text_about_print_column
---

Predicate to describe the Text of NewsArticle.

Use it like this: 
- [ #has_/text/_about_print_column :: Text ] or 
- [ has_text_about_print_column :: Text ] 

The number of the column in which the NewsArticle appears in the print edition.

Predicated describes that: 
[ #has_/domain  :: NewsArticle ]
( #has_/name :: has_text_about_print_column )
( #has_/range :: Text )

