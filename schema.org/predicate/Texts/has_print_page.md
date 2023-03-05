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

title: has_text_about_print_page
linkTitle: has_text_about_print_page

keywords: [print, page]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- print-page
- print_page
- printPage
- has_text_about_print_page
---

Predicate to describe the Text of NewsArticle.

Use it like this: 
- [ #has_/text/_about_print_page :: Text ] or 
- [ has_text_about_print_page :: Text ] 

If this NewsArticle appears in print, this field indicates the name of the page on which the article is found. Please note that this field is intended for the exact page name (e.g. A5, B18).

Predicated describes that: 
[ #has_/domain  :: NewsArticle ]
( #has_/name :: has_text_about_print_page )
( #has_/range :: Text )

